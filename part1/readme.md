# Member
<ul>
 <li> 09231 강영훈 </li>
</ul>

![Alt text](https://github.com/gogohs/skccBigData/blob/master/kangyounghun2.png)


## part1 hadoop cluster 구성 수행 내역 screen shot 참조
1. java 설치
2. CM server, agent 설치  (repo 정보 5.15.2 로 변경 수행)
3. maria DB 설치및 JDBC 드라이버 연결
4. CM web UI 실행 성공
5. CDH hadoop 클러스터 구성 완료
6. impala 설치 및 hue UI 실행
7. 이후 미수행
------

pre qualification

1. IP목록 DNS이름

![](DNS리스트.png)

2. 리눅스 버전

![](리눅스버전.png)

3. 마스터 노드 capa

4. repolist enabled

5. training 유저생성 skcc 그룹생성

CM 설치 진행
1. hostname이름 변경 및 실행

2. 데이터베이스 버전

3. 데이터베이스 목록 

4. JDBC 커넥터 JDK 설치

5. CDH 5.15.2 설치

6. HDFS, YARN, sqoop, hive, impala(데이터노드 전부다), hue 설치

데이터 적재
7. training 유저 생성(휴 브라우져 처음 생성시 만들면 자동 생성)

8. 테이블 생성 author, posts

9. 트레이닝 유저에 모든 테이블 접근권한

10. authot, posts 디렉토리 홈 디렉토리에 생성

11. 