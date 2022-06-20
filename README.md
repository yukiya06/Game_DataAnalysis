# 신규 게임 개발 방향 분석  
## 비디오게임 시장 매출 데이터 분석을 통한 다음 분기에 설계 할 게임 제안

* 데이터 분석 및 발표 : 안나 (Email: naan74532@gmail.com)
* 전체 발표자료 [PDF](https://github.com/yukiya06/Game_DataAnalysis/blob/main/DA_%EC%95%88%EB%82%98_%EC%8B%A0%EA%B7%9C%EA%B2%8C%EC%9E%84_%EA%B0%9C%EB%B0%9C%EB%B0%A9%ED%96%A5%EB%B6%84%EC%84%9D.pdf)

---
## 프로젝트 전체 목차
#### 1. 분석 목적
#### 2. 데이터 특성
#### 3. EDA 및 가설검증
  * 장르별 출시 게임 종류 및 매출
  * 가설 검증: 선호 게임에는 **트렌드**가 있다
    * **트렌드** 정의: 장르, 판매 국가, 연도, 게임 플랫폼, 판매 상위 게임에 특징 및 연관성이 있다.
  * 분석 상세
    * **지역**에 따른 선호 게임 장르 (통계적 검정)
    * **연도**별 게임 트렌드
    * **판매량** 상위 게임 특성분석 (게임 **플랫폼** 분석- 상관관계 분석)
#### 4. 게임 개발 전략 방향
  * 단기, 장기 전략

---
## 프로젝트 요약
### 1. 분석 목적
* 다음 분기 신규 게임 개발을 위한 인사이트 발굴 및 장기적 개발 방향 고찰

### 2. 데이터 특성
* 게임 타이틀 (11,330개), Platform (31개), 출시 연도 (1980년~2017년)
* 게임 장르 (12개), 국가별 매출실적 (북미/유럽/일본)
* 총 16,277 Set (1.9% 결측치 보정후)

### 3. EDA 및 가설검증
* 가설 검증: 선호 게임에는 **트렌드**가 있다
* **트렌드** 정의: 장르, 판매 국가, 연도, 게임 플랫폼, 판매 상위 게임에 특징 및 연관성이 있다.

* 분석 상세
  * 장르별 출시 게임 종류 및 매출
  <img width="800" alt="001" src="https://user-images.githubusercontent.com/91524805/174518510-64804ab6-6eea-401a-a3ea-fa7dfd849e1a.png">
  
  
  * 지역에 따른 선호 게임 장르 (통계적 검정)
  <img width="800" alt="002" src="https://user-images.githubusercontent.com/91524805/174519287-095006c3-f178-42dd-9e39-ab1186cbc496.png">
  <img width="800" alt="003" src="https://user-images.githubusercontent.com/91524805/174519317-b15c1126-b449-42b8-af82-006c35c013ed.png">
  
  * 연도별 게임 트렌드
    * 미국, 유럽, 일본과 같이 콘솔게임이 주류인 곳의 시장구조는 새로운 게임을 끊임없이 생산하여 단품으로 판매하고, 게임 타이틀의 매출에서 이익을 얻는 방식이다. 기기를 빠르게 보급하고, 더불어 해당 기기에서 구동되는 소프트웨어를 파는 것이 목적이다.
    * **1980년 ~ 1995년**:  콘솔게임의 Platform 경쟁이 시작되기 전으로, 대부분 한 종류의 Platform을 지원하는 게임이 출시되었다.
    * **1995년 ~ 2000년초**:  닌텐도가 강세인 시장에 소니가 참전하여 성공하면서 Platform 경쟁이 시작되었다. 기존에 출시된 게임들이 새로운 Platform으로 재출시되거나 처음부터 여러 Platform으로 출시되기 시작했다.
    * **2000년~**:  닌텐도, 소니, MS의 플랫폼 경쟁이 심화되며 여러 플랫폼으로 출시되는 게임이 증가했다. 2010년 이후 PC게임이 성장하면서 PC게임으로 함께 출시되기도 했다.

  * 판매량 상위 게임 특성분석
  <img width="800" alt="004" src="https://user-images.githubusercontent.com/91524805/174522690-443c3a26-f248-4368-8a54-a080eb34e6a4.png">
  <img width="800" alt="005" src="https://user-images.githubusercontent.com/91524805/174522699-b48be0c6-c478-4804-8fb5-03709257e154.png">
  <img width="800" alt="006" src="https://user-images.githubusercontent.com/91524805/174522704-a54df92f-159f-4152-82c9-e1400c761710.png">
  <img width="800" alt="007" src="https://user-images.githubusercontent.com/91524805/174522707-52a7ab0c-4422-45b2-ba62-80c79f0476d4.png">

### 4. 게임 개발 전략 방향
  <img width="800" alt="008" src="https://user-images.githubusercontent.com/91524805/174522844-2aa838d5-466f-41f4-8a39-3ff5a67124a0.png">

---
### 5. 참고자료
* [게임 매출 데이터 출처](https://www.kaggle.com/datasets/gregorut/videogamesales)
* [분산 분석](https://velog.io/@pyose95/Data-Analysis)
* [상관관계 분석](https://blog.naver.com/PostView.nhn?blogId=y4769&logNo=220227007641)
* [비디오 게임의 역사](https://namu.wiki/w/%EB%B9%84%EB%94%94%EC%98%A4%20%EA%B2%8C%EC%9E%84%EC%9D%98%20%EC%97%AD%EC%82%AC)
