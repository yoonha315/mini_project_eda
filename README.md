# 1. 👥팀 소개
🚗 **motor-chata**

<table>
  <tr align="center">
    <td><img src="https://github.com/jjhhyy0926/motor-chata/blob/main/assets/minha.png?raw=true" width="120px"><br><b>김민하</b></td>
    <td><img src="https://github.com/jjhhyy0926/motor-chata/blob/main/assets/jaehyun.png?raw=true" width="120px"><br><b>배재현</b></td>
    <td><img src="https://github.com/jjhhyy0926/motor-chata/blob/main/assets/jihye.png?raw=true" width="120px"><br><b>윤지혜</b></td>
    <td><img src="https://github.com/jjhhyy0926/motor-chata/blob/main/assets/yhjeon.png?raw=true" width="120px"><br><b>전윤하</b></td>
    <td><img src="https://github.com/motor-chata/motor-chata/blob/main/assets/ekthf.png?raw=true" width="120px"><br><b>정다솔</b></td>
    <td><img src="https://github.com/motor-chata/motor-chata/blob/main/assets/wlkstj.png?raw=true" width="120px"><br><b>홍진서</b></td>
  </tr>

  <tr align="left">
    <td>
        <b>- GitHub 총괄 관리
        <br>- 배급사별 데이터 분석 및 시각화</b></td>
    <td>
        <b>- 발표
        <br>- 대본 작성
        <br>- 관람등급 데이터 분석 및 시각화</b></td>
    <td>   
        <b>- 국가별 데이터 분석 및 시각화</b></td>
    <td>
        <b>- 데이터 전처리</b></td>
    <td>   
        <b>- 분기별 데이터 분석 및 시각화</b></td>
    <td>   
        <b>- 장르별 데이터 분석 및 시각화</b></td>
  </tr></table>

---
# 2. 프로젝트 기간
2026-02-19 ~ 2026-02-25

---
# 3. 프로젝트 개요
## 프로젝트명
### Movie EDA
## 프로젝트 소개
신생 배급사의 흥행을 위한 영화 데이터 분석
## 기획의도
대형 배급사 중심의 과점 구조와 시장 침체 상황에서 자본력이 흥행의 기준인가에 대한 문제를 제기하여 제한된 자원을 가진 신생 배급사가 관객 동원력을 극대화할 수 있는 데이터 기반 전략 도출한다.
## 기대효과
객관적 지표 기반의 전략을 수립하고, 시장 내 효율적인 포지셔닝을 결정하고, 작품 선정 단계에서 리스크 최소화한다. 
## 분석
- **변화하는 시장**
<br>최근 영화 시장이 전체적으로 침체되었으므로 불구하고, 신생 배급사가 기존 강자를 제치고 매출 1위를 기록하는 경우 발생, 돈이나 브랜드 파워가 아닌 작품 선택, 개봉 시기, 타겟 설정 등과 같은 복합적인 전략이 흥행 가능성이 있다.
- **분석 핵심 지표 : 관객 수**
<br>매출은 티켓 가격이나 특별관 운영 등과 같은 것에 영향을 받지만, 관객 수는 실제 시장의 수요를 가장 솔직하게 보여주는 지표이기 때문에 매출보다는 관객 수에 중점을 두었다.
- **시장 구조 및 상위권 벤치마킹**
<br>상위 배급사의 데이터를 분석하고, 어떤 장르나 등급에 집중하는지 패턴을 찾아내서 차별화 지점을 설정한다.
- **작품 속성별 효율성 확인**
<br>장르별, 관람 등급별, 국내/해외 영화별로 평균 관객 수를 비교해서 어떤 작품을 골랴야 효율적인지 판단 근거를 만든다.
- **최적의 개봉 타이밍 도출**
<br>분기별 데이터를 통해 성수기와 비수기의 패턴을 읽고, 대형작과의 정면 승부를 피하면서도 관객을 모을 수 있는 시기를 알아낸다.

# 4. 기술 스택

### 🛠 Development Environment
- PyCharm
- GitHub

### 🔧 Data Processing / Preprocessing
- Numpy
- Pandas
- Matplotlib
- Seaborn

### 🗄 Database
- 문화 빅데이터 플랫폼
- KOBIS 박스오피스 영화정보
