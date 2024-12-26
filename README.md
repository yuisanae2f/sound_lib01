# Local Sound (Audio) Organizing Library

- Duration : 2024.12.20 ~ 
- Last Update : 2024.12.22
---

여러 플랫폼에서 다운로드한 오디오를 관리하기 용이한 로컬프로그램 ( Windows )

---
### Function
1. **오디오 탐색 기능**
2. 오디오 플레이 기능
3. **오디오 메타데이터 CRUD**
   1. **오디오 길이**
   2. 오디오 그림
4. 오디오 카테고리 기능 CRUD
5. 오디오 태그 기능 CRUD
6. 오디오 별점 기능
7. 프로그램 사용 안내

---
### 제작 전략
CLI 로 먼저 기본 기능을 구현하고 GUI (Graphical User Interface)로 확장하여 텍스트 기반 인터페이스의 출력 형식을 개선할 예정입니다.

---

다음 추가할 기능 :
1. 메타데이터 출력 : 사용자가 특정 파일의 메타데이터를 확인할 수 있는 기능.
2. 파일 필터링 : 특정 파일 형식만 필터링 / 파일 크기별로 필터링 / 생성 일자
3. 에러 처리 강화 : 파일을 열거나 메타데이터 추출 과정 문제 발생시, 에러메세지를 출력하여 문제 알리기.
4. UI / UX 개선 : 사용자 경험을 위해 GUI로 확장 및 출력 형식 개선
---
추가하고 싶은 기능들 : 
1. 메타데이터가 존재할 경우 기존 메타데이터 업데이트
2. 파일 탐색 시 특정 조건에 맞는 파일만 추출
3. 파일명 중복 방지 : 
4. 메타데이터 세분화 저장 :
   1. duration, channels, sample_rate, bit_rate
   2. codec, bit_depth
---
인터페이스 추가하고 싶은 기능 : 
1. A, B 플랫폼에서 다운로드한 파일을 전체보기
2. 음질 시각화
3. 재생/멈춤/next/before/음질조절 버튼
     1. High/low pitch 노트 ver.
4. 오디오 위에 마우스 커서를 올려놓을시 메모 view
5. 오디오 위에 마우스 커서를 올려놓으면 표시 similar track 또는 same album track
    1. 비슷한 태그 검색, 제목, 랜덤 추천 기능 필요
