<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=FFB800&center=true&vCenter=true&width=435&lines=Hi+%F0%9F%91%8B%2C+I'm+YourName;Java+Architect;Backend+Wizard;Spring+Alchemist" alt="动态标题" />
</h1>

<p align="center">
  <a href="https://spring.io/" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring" width="40" height="40"/>
  </a>
  <a href="https://www.java.com" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/>
  </a>
  <a href="https://kafka.apache.org/" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/apache_kafka/apache_kafka-icon.svg" alt="kafka" width="40" height="40"/>
  </a>
  <a href="https://www.jenkins.io" target="_blank" rel="noreferrer">
    <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40" height="40"/>
  </a>
</p>

---

### 🧰 Java技术矩阵

#### 核心语言
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

#### 企业级框架
![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Hibernate](https://img.shields.io/badge/-Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![MyBatis](https://img.shields.io/badge/-MyBatis-FF6A00?style=flat-square&logo=apache&logoColor=white)

#### 构建工具
![Maven](https://img.shields.io/badge/-Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![Gradle](https://img.shields.io/badge/-Gradle-02303A?style=flat-square&logo=gradle&logoColor=white)

#### 数据库
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/-Elasticsearch-005571?style=flat-square&logo=elasticsearch)

#### 基础设施
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

#### 云平台
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws)
![Alibaba Cloud](https://img.shields.io/badge/-Alibaba%20Cloud-FF6A00?style=flat-square&logo=alibabacloud)

---

### 🏗️ 架构蓝图
```mermaid
graph TD
    A[Gateway] --> B[Service Discovery]
    B --> C[Config Server]
    C --> D{{Microservices}}
    D --> E[Auth Service]
    D --> F[Order Service]
    D --> G[Payment Service]
    E --> H[(MySQL Cluster)]
    F --> I[(Redis Sentinel)]
    G --> J[(Kafka Cluster)]
