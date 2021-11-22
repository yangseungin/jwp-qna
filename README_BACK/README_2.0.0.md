# JPA Relation Mapping
> version : 2.0.0

## 기능 목록

### 1. User
- 사용자 등록(회원가입)
- 사용자 정보 수정
    - 수정 대상 컬럼 : name, email, password
- 사용자 로그인을 위한 인증
    - ID, Password 일치 여부 확인
- 전체 사용자 수 조회
- 사용자 전체 목록 조회
- 사용자 ID 검색을 통한 사용자 수 조회
- 사용자 ID 검색을 통한 목록 조회
- 사용자 name 검색을 통한 사용자 수 조회
- 사용자 name 검색을 통한 목록 조회
- 사용자 상세 정보 조회
- 사용자 삭제(회원탈퇴)
    - 사용자 삭제 시 사용자가 등록한 Question도 삭제하기

### 2. Question
- 질문 등록
- 질문 수정
    - 수정 대상 컬럼 : title, contents
- 질문 전체 목록 수 조회
    - 목록 조회 시 deleted가 false인 값만 조회
- 질문 전체 목록 조회
- 사용자 ID 검색을 통한 질문 목록 수 조회
- 사용자 ID 검색을 통한 질문 목록 조회
- 질문 Title 검색을 통한 질문 목록 수 조회
- 질문 Title 검색을 통한 질문 목록 조회
- 질문 상세 정보 조회 : toString
- 질문 삭제
    - deleted 값 변경