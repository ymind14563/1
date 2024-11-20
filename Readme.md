
  
<div align="center">
<img src="https://github.com/user-attachments/assets/fe44fc15-a036-4146-bd50-b3e73483cc40" alt="oursalary" width="400"/>
</div>

## 🌱프로젝트 소개
* 주제 : 소규모 사업장을 위한 급여 관리 서비스 (급여명세서 자동생성)
* 기획 의도 : 관리자는 사원의 출퇴근 및 급여를 효율적으로 관리하고, 근로자는 자신의 출퇴근 기록과 생성된 급여 명세서를 간편하게 확인할 수 있도록 하여 **사원 관리 및 급여 명세서 관리의 편리성**을 극대화하는 것이 목표
* 기간 : 2023.05.08 ~ 2024.06.08 ( 30일 )

<br>
<br>

## 👨‍👩‍👦‍👦 Developer

### 🖥 Front-end
|이름|맡은 부분|
|---|---|
|유호균 [@ghrbsaod](https://github.com/ghrbsaod)|피그마, 페이지 중의 푸터,헤더, 메인 페이지 인터페이스 및 기능, 전체 기능 보수 |
|정 솔 [@lyssoi](https://github.com/lyssoi)|로그인,회원가입,계좌CRUD,특이사항CRUD,급여명세서CRUD,근로자의 회사등록 및 승인|
|유소영 [@ysycoding](https://github.com/ysycoding)|근로계약서 관리 CRUD, 사원정보 RUD,근무자의 캘린더 및 출퇴근, 특이사항 CRUD |        
  
<br>

### ⚙️ Back-end
|이름|맡은 부분|
|---|---|
|석원준 [@ymind14563](https://github.com/ymind14563)|사원 CRUD, 회사 CRUD 및 이미지 업로드, 은행 CR, 계좌 CRUD, AWS 배포(EC2, RDS, S3, CodeDeploy), Git Actions|
|심재우 [@RapiL89](https://github.com/RapiL89)|회원 CRUD, OAuth 2.0, SpringSecurity|
|송준상 [@DDunDDang](https://github.com/DDunDDang)|근로계약서 CRUD, 근무 상태 CRUD, 급여 명세서 CRD, PDF제작, EMAIL 전송, S3 업로드|

<br>  
<br>


## 📙 사용한 기술

| **Category**         | **Technologies**                                                                 |
|-----------------------|----------------------------------------------------------------------------------|
| **Backend**          | Java 11, Spring Boot v2.7.12, JPA(Hibernate)                                    |
| **Frontend**         | Next.js, TypeScript                                                            |
| **Database**         | MySQL v8.0.4                                                                   |
| **Cloud**            | AWS EC2, RDS, S3, CodeDeploy                                                   |
| **CI/CD**            | GitHub Actions                                                                |
| **Tool**             | Trello, GitHub      

<br>
<br>


## ❓ 주요 기술 채택 이유

- **Spring Boot** : 빠른 개발 환경과 생산성을 제공하며, 다양한 내장 기능으로 간편하게 웹 애플리케이션을 구현할 수 있어 채택.
- **JPA (Hibernate)** : 객체와 관계형 데이터베이스 간의 매핑을 쉽게 처리하고, 코드 중심의 데이터 관리를 위해 채택.
- **Next.js** : 서버 사이드 렌더링(SSR)과 정적 사이트 생성(SSG)을 지원하여 빠른 로딩 속도와 SEO 최적화를 위해 채택.
- **TypeScript** : 정적 타입 검사를 통해 코드 안정성과 가독성을 높이고, 유지보수를 용이하게 하기 위해 채택.
- **AWS (EC2, RDS, S3, CodeDeploy)** : 확장성과 안정성이 뛰어난 클라우드 서비스로, 다양한 애플리케이션 요구사항을 유연하게 대응하기 위해 채택.
- **GitHub Actions** : CI/CD 파이프라인을 자동화하여 개발과 배포 효율성을 높이기 위해 채택.


<br>
<br>

## 🧰 Architecture
![image](https://github.com/codestates-seb/seb43_main_033/assets/120348865/1f85e57c-2715-417f-af67-49d056ac8716)

<br>
<br>


## :notebook: ERD

![SEB_MAIN_33 - ERD-1](https://github.com/codestates-seb/seb43_main_033/assets/120554681/3e8557c7-9cae-4c75-9d71-2ed4a43731ec)

<br>
<br>

## :notebook: 사용자 요구사항 정의서

![234235_12](https://github.com/codestates-seb/seb43_main_033/assets/74657430/f890c110-f921-4326-a0c8-4705b6541cb3)
![234235_13](https://github.com/codestates-seb/seb43_main_033/assets/74657430/a28d0c10-e918-4268-8f0b-8efa3dece016)
![234235_14](https://github.com/codestates-seb/seb43_main_033/assets/74657430/ea623518-6373-437b-85e4-96124597871b)

<br>
<br>

## :notebook: 개발자 체크 리스트
  
![234235_10](https://github.com/codestates-seb/seb43_main_033/assets/74657430/cbe9b401-9844-46b1-9f1c-5d66f2a72e8c)
![234235_11](https://github.com/codestates-seb/seb43_main_033/assets/74657430/605ecbaf-edfb-4b52-bda5-25bf0022f391)

<br>
<br>

## :notebook: 테이블 명세서

[테이블 명세서](https://drive.google.com/file/d/1YY5cIBqij1XBdhOTJc_Pm_puu4e_yrMx/view?usp=drive_link)
![SEB_MAIN_33 - 테이블 명세서-1](https://github.com/codestates-seb/seb43_main_033/assets/120554681/0ce55fbc-9876-4e22-aec4-19929e2e6212)
![SEB_MAIN_33 - 테이블 명세서-2](https://github.com/codestates-seb/seb43_main_033/assets/120554681/a53fe744-c113-44b4-94ab-d073fe239fdf)

<br>
<br>

## :notebook: API 명세서

![스크린샷 2023-05-31 오후 5 40 55](https://github.com/codestates-seb/seb43_main_033/assets/120554681/8b299670-7a93-46b7-a571-97dc5b592cb9)

<br>
<br>

      
# 💡 Pages

<br />![234235_1](https://github.com/codestates-seb/seb43_main_033/assets/74657430/63232a40-24bf-43e5-9f8e-3b1268135682)
<br />![234235_8](https://github.com/codestates-seb/seb43_main_033/assets/74657430/e901ca30-5920-4dc3-8520-1dc1e7cf396e)
<br />![234235_9](https://github.com/codestates-seb/seb43_main_033/assets/74657430/557323f1-db48-46b2-8b34-305392ba8e48)
<br />![234235_2](https://github.com/codestates-seb/seb43_main_033/assets/74657430/bb8591d6-3ce6-4dad-914d-2e6809de585d)
<br />![234235_3](https://github.com/codestates-seb/seb43_main_033/assets/74657430/cec3acf9-f9cb-4680-bb89-6c03dc331a60)
<br />![234235_4](https://github.com/codestates-seb/seb43_main_033/assets/74657430/f6b34885-3b23-4721-b3d1-76962e235879)
<br />![234235_5](https://github.com/codestates-seb/seb43_main_033/assets/74657430/fb117af6-a0fd-402d-8f80-66888e72af59)
<br />![234235_6](https://github.com/codestates-seb/seb43_main_033/assets/74657430/e81bb797-b101-4037-bfeb-afb936924007)
<br />![234235_7](https://github.com/codestates-seb/seb43_main_033/assets/74657430/1d24c615-0a59-4366-be17-54934c381652)
