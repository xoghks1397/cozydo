## COZYDO
![cozydo](https://user-images.githubusercontent.com/62299120/108686876-5c79bd80-7539-11eb-95ed-ba52fc3539c1.png)

- Cozydo 웹 로고

## 팀원 소개

### Back-end

- 이태환, 이다운

### Front-end

- 한지윤,신가영,신다정

## 프로젝트 개요

### 진행기간

- 2021.01.06 ~ 2021.02.19

### 목표 및 기대효과

- 다양한 코로나 관련 정보를 한눈에 파악
- 정확한 장소 정보로 사용자 접근성 향상
- 이용가능한 장소를 지도에 다르게 표시하여 편의성 향상
- 리뷰를 통한 사용자간의 장소 정보 공유

### 주요 기능

- 지역에 따른 코로나 단계를 반영한 지도 서비스
- API를 이용한 일별,주별, 지역별 코로나 확진자 정보 실시간 제공
- 검색창, 카테고리별로 가고싶은 장소 검색 가능
- 검색 결과 거리순으로 리스트화(장소 이름, 위치 ,거리, 리뷰, 별점 보여줌)
- 선별 진료소도 검색 가능
- 상세 페이지에 아이콘으로 단계에 맞는 세부지침 확인가능, 좋아요와 댓글가능
- 집합금지 장소는 기존 마커와 다르게 표시
- jwt토큰과 email 인증을 통한 보안성을 높임
- 마이 페이지에선 작성한 리뷰, 좋아요 누른 장소 확인 가능 및 클릭 시 장소 상세 페이지로 이동 가능


## 기능 설명

### 메인 화면
<img src ="https://user-images.githubusercontent.com/62299120/124867162-83242680-dff8-11eb-844a-7ec850e3236d.png" width="500" height="250">

- 로고 밑 일일 학진자 정보 제공
- 현재 위치를 기반으로 거리두기 단계 자동 설정
- 검색창, 카테고리별로 가고싶은 장소 검색


### 검색 결과 화면(리스트)
![image](https://user-images.githubusercontent.com/62299120/124867301-c8e0ef00-dff8-11eb-8313-25f2fedb14b1.png)

- 검색 결과 거리순으로 리스트화
- 장소 이름, 위치, 거리, 리뷰 및 별점
- 장소 클릭 시, 장소 상세 페이지로 이동

### 검색 결과 화면(지도)
![image74](https://user-images.githubusercontent.com/62299120/124868896-6c330380-dffb-11eb-850d-7394b4bdd97a.png)

- 검색결과에 해당하는 장소 마커로 펴시
- 마커 클릭시 장소 이름 확인 가능
- 장소 이름 클릭 시 장소 상세 페이지로 이동
- 집합 금지 장소는 검은색으로 표시

### 장소 상세 페이지
![image82](https://user-images.githubusercontent.com/62299120/124868584-ee6ef800-dffa-11eb-8060-e64685d18596.gif)

- 장소 상세 내역 확인 가능
- 아이콘을 통해 한눈에 세부지침 확인
- 좋아요 및 댓글 기능
- 해당 장소에 대한 정보 수정 요청사항 등록 가능

### 코로나 확진자 정보 화면
![image87](https://user-images.githubusercontent.com/62299120/124869294-f3807700-dffb-11eb-8c4c-ee0644b79a2f.gif)

- 일일 확진자 정보(확진환자, 격리해제, 사망자)
- 일주일 간 일별 확진자 수 그래프
- 지역별 총 확진자 수, 일일 확진자 수 정보

### 마이페이지
![image103](https://user-images.githubusercontent.com/62299120/124869344-072bdd80-dffc-11eb-9bff-eb19d0d746d0.png)

- 좋아요 누른 장소 확인 가능
- 작성한 리뷰 확인 가능
- 로그아웃 및 회원탈퇴 기능

### 회원가입 시 이메일 인증
![image93](https://user-images.githubusercontent.com/62299120/124869386-1874ea00-dffc-11eb-9e3e-5885266acdf4.png)
![image95](https://user-images.githubusercontent.com/62299120/124869384-16ab2680-dffc-11eb-99f8-c7c9235606b4.png)
![image96](https://user-images.githubusercontent.com/62299120/124869371-13b03600-dffc-11eb-9a28-24c06a9e3dc3.png)
- 이메일 인증을 통해 보안성 증가하였고, 이메일 인증 후에만 로그인이 가능하게 구현

### db ead 
![erd](https://user-images.githubusercontent.com/62299120/108690605-e75cb700-753d-11eb-8da6-62257001c3c3.PNG)



### 기술 스택 및 시스템 구조
![시스템 구조](https://user-images.githubusercontent.com/62299120/108689828-eaa37300-753c-11eb-97bf-bd2b4ebf7e15.PNG)

![시스템 구조2](https://user-images.githubusercontent.com/62299120/108690070-3fdf8480-753d-11eb-8787-183756fe3fa7.PNG)
