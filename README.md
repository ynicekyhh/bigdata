# smartcar bigdata project

* 목표 : 스마트카 상태정보 데이터, 스마트카 주행정보 데이터를 활용하여 스마트카 이상 징후 예측, 스마트카 운전 패턴 군집을 추출한다. 

* 개발 환경 : 윈도우 X86 (RAM:16GM, HDD:256GB) -> window10 -> virtual box 3대(Linux server01,Linux server02,Linux server03)
    *  server01 (lx01.bigdata2017.com , 192.168.1.32, CentOs 6.9 ,Java 1.7)
         * Hadoop NameNode
         * Hadoop DataNode
         * HBase Management
         * HBase Region Server
         * Cloudera Management
         * PostgresSQL
         
    *  server02 (lx02.bigdata2017.com , 192.168.1.54, CentOs 6.9 ,Java 1.7)
    
         * Hadoop DataNode 
         * Oozie     
         * Storm
         * HBase Resion     
         * Redis     
         * Hive/Spark
         * Zeppelin         
         * Zookeeper 
         * Kafka
         * Hume             
         * Flume
         
    *  server03 (lx03.bigdata2017.com , 192.168.1.55, CentOs 6.9 ,Java 1.7)
         * Hadoop DataNode
         * HBase Resion
         * Impala
         * Sqoop
         

* 아키텍쳐
![software architecture](https://github.com/yonwon01/bigdata/blob/master/software architecture.png)

* 데이터셋 : 스마트카 상태 데이터와 스마트카 실시간 주행 데이터 시뮬레이터 개발
   ##### 시뮬레이터 코드(https://github.com/yonwon01/smartcarlog)

![domain](https://github.com/yonwon01/bigdata/blob/master/domain.png)




























