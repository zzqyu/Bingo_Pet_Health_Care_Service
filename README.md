# Bingo_Pet_Health_Care_Service
## Android Application

<a href="https://play.google.com/store/apps/details?id=kr.co.jmsmart.bingo"><img src="./playstore.jpg" width="30%"/></a>

## 1. 서비스 개요
* 반려견의 건강 관리를 위한 웨어러블 디바이스와 코칭 솔루션 서비스(APP)

## 2. 구성 요소 및 기술
### 2.1. 구성 요소 
#### 2.1.1. 웨어러블 디바이스
* Bluetooth - ble
#### 2.1.2. 서버
* 서버 : Amazon Web Service
  * 반려견 활동 데이터 관리 및 코칭 솔루션 제공 목적 
  * CPU : AWS CPU 1 Core
  * Memory : AWS RAM 4GB
  * HDD : AWS HDD 20GB
  * Ethernet :１Gbps Ethernet
* Rest API : Spring Framework
* DBMS : Mysql
#### 2.1.3. 안드로이드 앱
* OS : Android 6.0이상
* 언어 : JAVA 8
* MVVM(Model - View - ViewModel) 패턴 사용
* 사용 Library 
  * [FastBle (Apache License 2.0)](
https://github.com/Jasonchenlijian/FastBle) : BLE 관련
  * [Timeline-View (Apache License 2.0)](https://github.com/vipulasri/Timeline-View) : Layout 관련
  * [MPAndroidChart (Apache License 2.0)](https://github.com/PhilJay/MPAndroidChart) : 그래프 Layout 관련
  * [GraphView (Apache License 2.0)](https://github.com/jjoe64/GraphView) : 그래프 Layout 관련
  * [gson (Apache License 2.0)](https://github.com/google/gson
) : Json 관련
  * [FloatingActionButton (Apache License 2.0)](https://github.com/Clans/FloatingActionButton):커스텀 위젯 및 뷰 라이브러리
  * [SwipeMenuListView (MIT)](https://github.com/baoyongzhang/SwipeMenuListView):커스텀 위젯 및 뷰 라이브러리

![Component](./component.jpg)
![설명](./설명.jpg)