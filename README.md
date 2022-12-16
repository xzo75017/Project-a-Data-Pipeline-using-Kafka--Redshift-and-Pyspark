# PySpark-Project-Build-a-Data-Pipeline-using-Kafka-and-Redshift

- Understanding the project overview
- Introduction to PySpark
- Need for PySpark integration
- Introduction to Confluent Kafka
- Introduction to Amazon Redshift
- Installation and Setup of Confluent Kafka
- Understanding the concept of ETL
- Difference between ETL and ELT
- Creating cluster in Amazon Redshift
- Create a database and table in the Redshift cluster
- PySpark integration with Confluent Kafka
- PySpark integration with Amazon Redshift

Command of Kafka

To start conflunt Kafka 

confluent local services start


To get into bash shell of different containers

```docker exec -i -t ee83539a5bfe bash```


To create topic

```kafka-topics --create --topic airline-topic --bootstrap-server localhost:9092 --replication-factor 1 ```





To list of topics

``` kafka-topics --list --bootstrap-server localhost:9092 ```
