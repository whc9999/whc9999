### 🛠️ Tech Stack

**Backend**  
<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white"/> 
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/> 
<img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white"/> 
<img src="https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=flat-square&logo=spring&logoColor=white"/> 
<img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black"/>

**AI / LLM**  
<img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/> 
<img src="https://img.shields.io/badge/Cohere-395CFF?style=flat-square"/>

**Prompt Engineering**  
<img src="https://img.shields.io/badge/Structured_Output-000000?style=flat-square&logo=openai&logoColor=white"/> 
<img src="https://img.shields.io/badge/Few--shot_Prompting-4F46E5?style=flat-square"/>

**Database & Cache**  
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/> 
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/> 
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>

**Messaging**  
<img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white"/>

**Infra & DevOps**  
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white"/> 
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/> 
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/> 
<img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white"/> 
<img src="https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=white"/>

**Tools & Communication**  
<img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white"/> 
<img src="https://img.shields.io/badge/Confluence-172B4D?style=flat-square&logo=confluence&logoColor=white"/> 
<img src="https://img.shields.io/badge/Slack-4A154B?style=flat-square&logo=slack&logoColor=white"/> 
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/> 
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>

**Monitoring**  
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white"/>
<img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"/>
<img src="https://img.shields.io/badge/Loki-F2C037?style=flat-square&logo=grafana&logoColor=black"/>

---
### Profile

- 홍익대학교 컴퓨터공학과 (2023.03 ~ )
- 홍익대학교 컴퓨터공학과 학술학회 P.C.R.C. - 36기 (2024.09 ~ 2024.12)
- 홍익대학교 멋쟁이사자처럼 - 13기 BE (2025.03 ~ 2025.12)
- 홍익대학교 멋쟁이사자처럼 - 14기 BE 운영진 (2025.01 ~ )
- 신촌 연합 IT 창업동아리 CEOS - 23기 BE (2026.03 ~ 2026.08)
- 신촌 연합 IT 창업동아리 CEOS - 24기 BE 파트장 운영진 (2026.08 ~ )

---

### 🚀 Featured Projects & Experience

- **[JobDri](https://github.com/JobDri-Developer/BackEnd)** : AI 기반 자기소개서 분석 및 첨삭 플랫폼 (2026.04 ~ 진행중)
  - `RabbitMQ` 기반 비동기 AI 분석 파이프라인을 구축하여 API 서버와 AI Worker를 분리하고, 분석 상태 관리 및 재시도 가능한 구조를 설계.
  - `Structured Output` 이후에도 서버 검증 계층을 추가하여 원문 문장 검증, 상태값 검증, 문장 위치 계산, 중복 제거 등 AI 응답의 신뢰성을 강화.
  - `Few-shot Prompting`과 평가 전용 Runner를 도입하여 프롬프트 품질을 반복적으로 검증하고 AI 분석 결과의 일관성을 개선.
  - `Cohere Embedding`을 활용한 유사 Few-shot 검색 구조를 설계하고, `Few-shot Prompting` 및 평가 전용 Runner를 도입하여 프롬프트 품질과 AI 분석 결과의 일관성을 개선.

- **[땅!땅!땅!](https://github.com/ddang-ddang-ddang/hongikLaw_BE.git)** : AI 연동 및 계층형 토론 기반 온라인 재판 플랫폼 (2025.09 ~ 2025.12)
  - `Spring AOP` 내부 호출(Self-Invocation) 문제를 분석하고 비동기 처리 구조를 개선하여 API 응답 시간 **5.22초 ➡️ 0.11초**로 단축.
  - `Slack Webhook` 연동을 통한 실시간 에러(HTTP 500) 및 유저 신고 모니터링 파이프라인 구축.

- **[SIMVEX](https://github.com/Bamti-DOSA/dosa-backend.git)** : 3D 기계 부품 조립 및 AI 튜터 플랫폼 (2026.02)
  - `AWS S3 Presigned URL`을 활용하여 대용량 3D 모델 파일 서빙 시 발생하는 백엔드 트래픽 병목 해소.
  - `GitHub Actions`를 이용한 CI/CD 파이프라인 구축.

- **[멋쟁이사자처럼 14기](https://github.com/likelion-14th-page/likelion-14th-BE.git)** : 지원자 데이터 관리 웹 서비스 (2026.01 ~ )
  - 크로스 도메인 환경의 `CORS` 및 세션 로그인 문제 해결.
  - `Swagger` 및 `@JsonAlias`를 활용한 협업 효율 개선.

---

### 🔗 Contact & Channel
- **Tech Blog** : [wooh.log](https://velog.io/@whc9999/posts)
- **Email** : [whc3377@gmail.com](mailto:whc3377@gmail.com)
