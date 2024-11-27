## 1인가구를 위한 종합적인 생활 솔루션을 제공하기 위한 소비 트렌드 분석

> 1인 가구의 소비트랜드를 분석을 통한 기업의 맞춤형 판매 전략 수립 및 시스템 구축

### 데이터 수집 
- 가계동향조사 연간자료(지출, 2019~2023) - 전체가구_1인이상 - MDIS(마이크로데이터 통합서비스 (https://kosis.kr/statHtml/statHtml.do?orgId=101&tblId=DT_1L9U005&conn_path=I2&docId=03936&markType=S&itmNm=%EC%A0%84%EA%B5%AD)
  

### 데이터 전처리 
- 연도, 성별, 소비품목에 따른 지출금액 분석
- 연령대는 20대, 30대, 40대, 50대, 60대, 70대이상으로 구분
- 각 변수의 박스플롯, Z-score 등을 활용하여 이상치 식별 / 이상치 제거 또는 보정 여부 결정
- [1차 이상치제거 전체가구]
 ![이상치제거_전체가구](https://github.com/user-attachments/assets/1230ce68-ce0a-4e14-9b1d-701d79c51662)

- [2차 이상치제거 1인가구]
![이상치제거_1인가구](https://github.com/user-attachments/assets/26e91f76-aa62-4473-beb3-673cc22806be)

### EDA 
- 데이터 크기, 결측치, 이상치 등 데이터 품질 확인
- 각 변수의 기초통계량(평균, 중앙값, 표준편차, 최소값, 최대값 등) 확인\

 ![1인가구_소비물품](https://github.com/user-attachments/assets/c0c0dc36-fd44-46ae-9c3c-a6d5a3ed55f0) ![1인가구_소비물품_2](https://github.com/user-attachments/assets/65526175-49c1-4cf0-aec8-1dfdfaf1a254)
 
- 연속형 변수 간 상관관계 분석
  
![상관분석](https://github.com/user-attachments/assets/af5f3b68-4c15-4584-a7c9-66754c659391)

- 독립변수와 종속변수(지출액)의 다중회귀분석

![다중회귀분석](https://github.com/user-attachments/assets/76cd9790-f51e-47d4-aae7-4622d741de93)




### 시각화 
- 파이 차트, 막대차트 등을 이용해 연령대별, 품목별 소비 트렌드를 시각화 함.
- 각 변수별로 상관분석한 내용을 시각화 함.
- Folium을 이용하여 구별 마트 본포 확인

  ![마트분포](https://github.com/user-attachments/assets/869537c3-d58c-472b-b956-acac377f466b)


● 수행도구
Git / github / Sourcetree / vscode / python / numpy / pandas / google sheet

