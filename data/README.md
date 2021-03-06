# Datasets
This page lists the 11 datasets used in our journal submission, which are freely accessible for research purposes. Some of the logs are production data released from previous studies, while some others are collected from real systems in our lab environment.

Among these datasets, 6 of them (Hadoop, Spark, Windows, Linux, Apache, Thunderbird) are collected for the extended experiments in our journal submission. For datasets (BGL, HPC, HDFS, Zookeeper, Proxifier) used in the previous [conference paper](http://ieeexplore.ieee.org/document/8029742/), we host only sample datasets (2k lines) here due to their large size. If you are interested in the full datasets, please request the [logs at Zenodo](https://doi.org/10.5281/zenodo.1144100) or visit the source links wherever applicable. We will send you the full datasets upon requests.

Details
--------
| Software System          |         Dataset Name         |  #Messages  |   Message Length   | #Events | Source Link | 
| :----------------------- | :--------------------------: | :--------: | :---------: | :------------------: | :------------------: |
| **Distributed systems**     |                              |            |             |          |                      |
| HDFS                     |   [HDFS](./2kHDFS)    | 4,747,963 | 10-102  |  376  |     [Link](http://iiis.tsinghua.edu.cn/~weixu/sospdata.html) |
| Hadoop                   |      [Hadoop](./Hadoop)      |    2,000    |   6-48    |        116        | |
| Spark                    |       [Spark](./Spark)       |    2,000    | 6-22    |     36   | |
| Zookeeper                |   [Zookeeper](./2kZookeeper)   | 74,380  |   8-27    | 80  |
| **Operating systems**    |                              |            |             |          |                      |
| Windows                  |     [Windows](./Windows)     | 2,000 | 6-22 | 50  |                |
| Linux                    |       [Linux](./Linux)       | 2,000 |   7-25    |  123  |              |
| **Server applications**     |                              |            |             |          |                      |
| Apache Web server        |      [Apache](./Apache)      | 2,000 |   5-10    |  6  |               |
| **Supercomputers**       |                              |            |             |          |                      |
| Blue Gene/L              |         [BGL](./2kBGL)        | 4,747,963 |  10-102  | 376 |  [Link](https://www.usenix.org/cfdr-data) |
| HPC                      |         [HPC](./2kHPC)         |    433,490    |   6-104   | 105  |            |
| Thunderbird              | [Thunderbird](./Thunderbird) |  2,000  | 11-133 | 154  |                |
| **Standalone software** |                              |            |             |          |                      |
| Proxifier                |   [Proxifier](./2kProxifier)   |    10,108    |   10-27    |  8  |               |

### Publications using these datasets
+ [**CCS'17**] Min Du, Feifei Li, Guineng Zheng, Vivek Srikumar. [DeepLog: Anomaly Detection and Diagnosis from System Logs through Deep Learning](https://acmccs.github.io/papers/p1285-duA.pdf). ACM Conference on Computer and Communications Security (CCS), 2017.
+ [**TDSC'17**] Pinjia He, Jieming Zhu, Shilin He, Jian Li, Michael R. Lyu. [Towards Automated Log Parsing for Large-Scale Log Data Analysis](http://ieeexplore.ieee.org/document/8067504/). IEEE Transactions on Dependable and Secure Computing (TDSC), 2017.
+ [**ICWS'17**] Pinjia He, Jieming Zhu, Zibin Zheng, Michael R. Lyu. [Drain: An Online Log Parsing Approach with Fixed Depth Tree](http://jiemingzhu.github.io/pub/pjhe_icws2017.pdf). IEEE International Conference on Web Services (ICWS), 2017.
+ [**ICSE'16**] Qingwei Lin, Hongyu Zhang, Jian-Guang Lou, Yu Zhang, Xuewei Chen. [Log Clustering Based Problem Identification for Online Service Systems](http://ieeexplore.ieee.org/document/7883294/). International Conference on Software Engineering (ICSE), 2016.
+ [**DSN'16**] Pinjia He, Jieming Zhu, Shilin He, Jian Li, Michael R. Lyu. [An Evaluation Study on Log Parsing and Its Use in Log Mining](http://jiemingzhu.github.io/pub/pjhe_dsn2016.pdf). IEEE/IFIP International Conference on Dependable Systems and Networks (DSN), 2016.
+ [**ISSRE'16**] Shilin He, Jieming Zhu, Pinjia He, Michael R. Lyu. [Experience Report: System Log Analysis for Anomaly Detection](http://jiemingzhu.github.io/pub/slhe_issre2016.pdf). IEEE International Symposium on Software Reliability Engineering (ISSRE), 2016.
+ [**KDD'09**] Adetokunbo Makanju, A. Nur Zincir-Heywood, Evangelos E. Milios. [Clustering Event Logs Using Iterative Partitioning](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.503.7668&rep=rep1&type=pdf). ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (KDD), 2009.
+ [**SOSP'09**] Wei Xu, Ling Huang, Armando Fox, David A. Patterson, Michael I. Jordan. [Detecting Large-Scale System Problems by Mining Console Logs](https://www.sigops.org/sosp/sosp09/papers/xu-sosp09.pdf). ACM Symposium on Operating Systems Principles (SOSP), 2009. 
+ [**DSN'07**] Adam J. Oliner, Jon Stearley. [What Supercomputers Say: A Study of Five System Logs](http://ieeexplore.ieee.org/document/4273008/). IEEE/IFIP International Conference on Dependable Systems and Networks (DSN), 2007.

### License
The log datasets are freely available ONLY for research purposes. 

[LogPAI Team](https://github.com/orgs/logpai/people), 2018
