#1010data
##Overview
Provides cloud-based software platform and services for big data business analytics and database publishing.

##Advantage
1.	Unifies data warehousing and analysis on the same remote platform (analytical platform as a service [APaaS]).
2.	Better performance, competitive scalability.

##Disadvantage
1.	Keeps all historic copies of data.

##Source
1.	http://en.wikipedia.org/wiki/1010data
2.	https://www.1010data.com/products/
3.	http://waynekernochanblog.blogspot.com/2010/08/1010data-operating-well-in-parallel.html
<br></br>

#Accumulo
##Overview
Sorted, distributed key/value store based on Google’s BigTable technology and built upon Apache Haddop, ZooKeeper, and Thrift. Low-latency NoSQL/non-relational database.

##Advantage
1.	Security: Column visibility that controls data access at the cell-level without degrading performance.
2.	Performance: operate and perform at massive scale with low administrative overhead; supports interactive queries and high throughput.
3.	Flexibility: Easily handles multi-structured and sparse datasets without extensive data modeling.

##Disadvantage
1.	Never splits rows across tablets.

##Source
1.	http://en.wikipedia.org/wiki/Apache_Accumulo
2.	https://accumulo.apache.org/
3.	http://sqrrl.com/product/accumulo/
4.	http://archive.cloudera.com/accumulo/cdh/1.4/accumulo/bulkIngest.html
<br></br>

#Actian Ingres
##Overview
Open-source SQL relational database management system (RDBMS) for large commercial and government applications.

##Advantage
1.	ACID-compatible and fully transactional. 
2.	Scalable in terms of data growth; tight security features; involved data can withstand failures.

##Disadvantage
1.	Installation not quite user-friendly (demands more knowledge).
2.	Smaller user community than PostgresSQL, therefore harder to obtain support.
3.	Releases prone to have bugs.

##Source
1.	http://en.wikipedia.org/wiki/Ingres_%28database%29
2.	http://www.techopedia.com/definition/3496/ingres
3.	http://community.actian.com/forum/comp-databases-ingres/4380-comparing-ingres-vs-postgresql.html
<br></br>

#Actian Matrix
##Overview
High-performance RDBMS for broad-spectrum analytical processing.

##Advantage
1.	Massively parallel, columnar, compressed, compiled approach delivers high performance.
2.	Fast, scalable, and integrated analytics.

##Disadvantage
1.	Proprietary.

##Source
2.	http://www.odbms.org/2014/08/actian-matrix-highest-performing-analytics-database/
3.	http://wwwcdn.actian.com/wp-content/uploads/2014/01/Actian-Matrix-Datasheet.pdf
<br></br>

#Actian PSQL
##Overview
ACID-compliant DBMS developed by Pervasive Software.

##Advantage
1.	Optimized for embedding in applications.
2.	Supports stand-alone, client-server, peer-to-peer and software-as-a-service (SaaS) deployment due to its file-based architecture enabling partitioning of data for multitenancy needs.
3.	Supports both structured (RDBMS) and less structured data.

##Disadvantage
1.	Lacks Unicode support in the RDBMS layer.
2.	Lacks the ability to perform distributed transactions
3.	Lacks some data warehousing, data mining, and reporting services commonly seen in other database environments due to its purpose of being an embedded database engine.

##Source
http://en.wikipedia.org/wiki/Pervasive_PSQL
http://www.devx.com/dbzone/Article/20006
<br></br>

#Actian Vector
##Overview
Relational database software for data analysis using vector technology.

##Advantage
1.	High performance, price/performance and energy efficiency (process data faster than most other relational databases).
2.	Requires few hardware and almost no database tuning (user-friendly).

##Disadvantage
1.	Proprietary.

##Source
1.	http://www.ticout.com/descargas/Actian-Vector-Datasheet.pdf
2.	http://www.odbms.org/wp-content/uploads/2014/08/WP01-ActianVector-0424.pdf
<br></br>

#Actian Versant
##Overview
Object-oriented database that can be classified as NoSQL. Memory model is the database schema model.

##Advantage
1.	No need for joins and other SQL commands (stores complex data and relationships between data directly, without mapping to relational rows and columns).
2.	Automatically perform schema modifications (requires minimal administration).

##Disadvantage
1.	Weak query support.

##Source
1.	http://www.databasemonth.com/database/actian-versant
2.	http://en.wikipedia.org/wiki/Object_database#Comparison_with_RDBMSs
3.	http://en.wikipedia.org/wiki/Db4o
<br></br>

#Adabas
##Overview
Inverted list database management system for enterprise transactions.

##Advantage
1.	Highly efficient and reliable performance.
2.	Supports XML and web services deployment.

##Disadvantage
1.	Less well-known; small client population.
2.	Need training before using the system.

##Source
1.	http://en.wikipedia.org/wiki/ADABAS
2.	http://www.softwareag.com/corporate/products/adabas_natural/adabas/overview/default.asp
3.	http://www.computerweekly.com/feature/Adabas-offers-more-than-a-legacy
<br></br>

#Aerospike
##Overview
Flah-optimized, in-memory open-source NoSQL database system. Operates in three layers: flash optimized data layer, self-managed distribution layer, and cluster-aware client layer.

##Advantage
1.	Replicated distribution layer across data center; ensures consistency and safeguard against failure.
2.	Data stored in solid state drives, RAM (quick availability), and traditional rotational media.
3.	High performance and reduced latency.  

##Disadvantage
1.	Niche exclusive to advertising sector; less well-known in other sectors compared to other NoSQL database systems.

##Source
1.	http://en.wikipedia.org/wiki/Aerospike_database
2.	https://www.aerospike.com/wp-content/uploads/2014/03/Aerospike-Impact-Report-12-Mar-2014.pdf
<br></br>

#Cassandra
##Overview
NoSQL distributed storage system for managing large structured data spread out across many commodity servers).

##Advantage
1.	Open-source.
2.	Economical and requires no new equipment.
3.	Decentralization (always-on architecture): each node in a cluster has the same role, therefore providing high availability with no single point of failure (Disaster-prevention).
4.	Elastic scalability; fast linear-scale performance; flexible data storage; easy data distribution; operational simplicity; transaction support. 
5.	Column-oriented and schema-free.

##Disadvantage
1.	No support for ACID transaction.
2.	Searching is complicated.

##Source
1.	http://en.wikipedia.org/wiki/Apache_Cassandra
2.	http://planetcassandra.org/what-is-apache-cassandra
3.	http://www.datastax.com/what-we-offer/products-services/datastax-enterprise/apache-cassandra
4.	http://www.edureka.co/blog/apache-cassandra-advantages
5.	http://www.ibm.com/developerworks/library/os-apache-cassandra
<br></br>

#CouchDB
##Overview
NoSQL database that uses JSON for data storage and JavaScript for querying using MapReduce, and HTTP for API. 

##Advantage
1.	Open-source.
2.	Emphasis on ease of usage: Bi-directional synchronization and off-line operation
3.	ACID support: Multi-Version Concurrency Control (MVCC) that avoids the need to lock database during writes; supporting multi-user access.
4.	Data stored as independent documents with own self-contained schema.
5.	Eventual consistency providing availability and partition tolerance.

##Disadvantage
1.	JSON file – large.
2.	No built-in full text search.
3.	No support for transactions, enforcing uniqueness of one field across all documents.

##Source
1.	http://en.wikipedia.org/wiki/CouchDB
2.	http://stackoverflow.com/questions/7858699/disadvantages-of-couchdb
<br></br>

#MongoDB
##Overview
Cross-platform document-oriented NoSQL database.

##Advantage
1.	Open-source.
2.	JSON-like documents with dynamic schemas, yielding faster and easier data integration.
3.	Ad-hoc queries: search by field, range queries, and regular expression searches.
4.	Field can be indexed.
5.	Replicated sets providing high availability.
6.	Supports most SQL-like queries.

##Disadvantage
1.	Consumes a lot of disk-space.
2.	Replica-set have a limit of 12 nodes.
3.	32-bit version can only handle a small amount of data (2gb).
4.	Costly consulting prices.

##Source
1.	http://en.wikipedia.org/wiki/MongoDB
2.	http://www.itexto.com.br/devkico/en/?p=44&utm_content=bufferac855&utm_source=buffer&utm_medium=twitter&utm_campaign=Buffer
<br></br>

#MySQL
##Overview
Relational database management system; most popularly used in web applications.

##Advantage
1.	Open-source.
2.	Wide usage.
3.	Easy to use.
4.	Security; solid data security layers and customized rights for access; password encryption.
5.	Free download for most uses.
6.	Fast.
7.	Scalable.
8.	Good safeguard against memory leaks.

##Disadvantage
1.	Does not comply with the full SQL standard for some implemented functionalities.
2.	Limited by hard disk performance, most obviously affecting write latency.

##Source
1.	https://www.novell.com/documentation/nw65/web_mysql_nw/data/aj5bj52.html
2.	http://en.wikipedia.org/wiki/MySQL
<br></br>

#MySQL Cluster
##Overview
Storage engine that provides shared-nothing clustering and auto-sharding for MySQL.

##Advantage
1.	High availability and high throughput with low latency.
2.	Near linear scalability.
3.	No point of failure provided given correctly set-up cluster.

##Disadvantage
1.	Noncompliance with some SQL Syntax.
2.	Limitations in transaction and error handling.

##Source
1.	http://en.wikipedia.org/wiki/MySQL_Cluster
2.	http://dev.mysql.com/doc/refman/5.0/en/mysql-cluster-limitations.html
<br></br>

#MySQL Fabric
##Overview
Integrated system for managing collections of MySQL servers.

##Advantage
1.	Open-source.
2.	High availability: builds upon MySQL replication to provide automated failure detection and failover.
3.	Data sharding: partition rows from selected tables into a number of shards to achieve scaling out of both reads and writes.

##Disadvantage
1.	Each time a change is made to the data, updates must be made to the application code.

#Source
1.	http://dev.mysql.com/downloads/fabric/
2.	https://www.scalebase.com/mysql-fabric-vs-scalebase-the-supermarket-example/
<br></br>

#Oracle Big Data Appliance
##Overview
Hardware and software designed to integrate both structured and unstructured enterprise data.

##Advantage
1.	Compatible with other Oracle software, providing a complete suite for Big Data.

##Disadvantage
1.	Cost a lot of money – infeasibility for smaller companies. 

##Source
1.	http://en.wikipedia.org/wiki/Oracle_Big_Data_Appliance
2.	http://searchoracle.techtarget.com/feature/The-Oracle-big-data-strategy-Weighing-appliance-vs-commodity
<br></br>

#Oracle Big Data Cloud
##Overview
Provides Hadoop as a secure, managed, elastic, and fully-integrated service.

##Advantage
1.	On-demand: rapid and self-service provisioning.
2.	Elasticity and scaling to handle large data.
3.	Managed: automated cluster lifecycle management through tooling and orchestration.
4.	Integrated with other cloud and on-premise service.

##Disadvantage
1.	Expensive.
##Source
1.	https://cloud.oracle.com/bigdata?tabID=1410590925790
<br></br>

#Oracle Coherence
##Overview
Java-based in-memory data grid designed for better reliability, scalability and performance compared with traditional RDBMS.

##Advantage
1.	Highly horizontally scalable and fault-tolerant.
2.	Replicated data processing engline providing rich data processing to where data is located.
3.	Support for various languages.
4.	Ability to integrate with other services.

##Disadvantage
1.	Proprietary.
2.	Cache implementation is done only in Java.

##Source
1.	http://en.wikipedia.org/wiki/Oracle_Coherence
2.	https://community.oracle.com/thread/2447944
<br></br>

#Oracle Database
##Overview
Object-relational database management system.

##Advantage
1.	Widely used – community for help.
2.	Ported to more platforms than any other competitor.
3.	Full support of SQL.
4.	Functionality, reliability, and flashback technology enabling data recovery.

##Disadvantage
1.	Costly.
2.	Learning curve associated with using Oracle SQL compared to competitors.

##Source
1.	http://en.wikipedia.org/wiki/Oracle_Database
2.	http://www.erpgreat.com/oracle-database/advantage-of-oracle-database.htm
3.	http://www.ehow.com/list_7684620_advantages-oracle-databases.html
4.	http://www.ehow.com/list_6309384_advantages-disadvantages-oracle-sql.html
<br></br>

#Oracle Endeca Server
##Overview
Hybrid search-analytical database.

##Advantage
1.	Organizes data into a flexible data model to reduce the need for upfront modeling.

##Disadvantage
1.	Standalone nature of its architecture.
2.	Costly.

##Source
1.	http://www.oracle.com/technetwork/middleware/endecaserver/overview/index.html
2.	http://www.clearpeaks.com/blog/big-data/data-discovery-analysis-making-best-oracle-endeca-information-discovery
<br></br>

#Oracle Exadata
##Overview
Database platform for running Oracle Database (Database as a service).

##Advantage
1.	Supports both OLTP (transactional) and OLAP (analytical) database systems.
2.	Largest user community of for running Oracle database.
3.	Every user uses the same identical system, which facilitates troubleshooting.

##Disadvantage
1.	Limited to one vendor for hardware and software.
2.	Expensive.
3.	Complex hardware and software.

##Source
1.	http://en.wikipedia.org/wiki/Oracle_Exadata
2.	http://www.oracle.com/technetwork/issue-archive/2011/11-mar/o21interview-302468.html
3.	http://www.nyoug.org/Presentations/2012/June/Ault_Exadata.pdf
<br></br>

#Oracle Exalytics
##Overview
In-memory business intelligence machine that is an optimized system for speed-of-thought analysis (Analytics as a service).

##Advantage
1.	Complete suite of solutions (mature service). 
2.	Provides Oracle Essbase which is the mostly widely deployed OLAP technology for analytics.

##Disadvantage
1.	Expensive.

##Source
1.	https://www.oracle.com/engineered-systems/exalytics/index.html
2.	http://www.oracle.com/us/corporate/features/exalytics-hana-1559434.html
<br></br>

#Oracle NoSQL
##Overview
NoSQL-type distributed key-value database.

##Advantage
1.	Simple model using key-value pairs with major and sub-keys.
2.	Supports ACID transactions and JSON.
3.	Integrated with Oracle Database and Hadoop.
4.	High availability, scaliability, and dynamic add capacity.

##Disadvantage
1.	Not widely used in the NoSQL sector.
2.	Expensive.

##Source
1.	http://en.wikipedia.org/wiki/Oracle_NoSQL_Database
2.	http://www.forbes.com/sites/greatspeculations/2014/04/04/nosql-databases-oracles-big-opportunity/
<br></br>

#Oracle TimesTen
##Overview
In-memory RDBMS.

##Advantage
1.	Persistence and recoverability.
2.	Data located in RAM, yielding no need for disk I/O for data operation.
3.	Short, consistent response time and high throughput.

##Disadvantage
1.	Costly.

##Source
1.	http://en.wikipedia.org/wiki/TimesTen
<br></br>

#Postgres-XL
##Overview
PostgreSQL-based database cluster.

##Advantage
1.	Open-source.
2.	Scalability and cluster-wide consistency.
3.	Multi-tenant security.
4.	Full ACID support.
##Disadvantage
1.	Limitation in massively parallel processing (MPP).

##Source
1.	http://www.postgres-xl.org/
<br></br>

#PostgreSQL
##Overview
Object-relational DBMS emphasizing extensibility and standards-compliance in data storage.

##Advantage
1.	Open-source.
2.	Safeguards against over-deployment.
3.	Large community of users and professionals for support.
4.	Low cost.
5.	Reliabilitiy, stability, extensibility, and cross-platform compatibility.

##Disadvantage
1.	Lack of integrated replication solution.
2.	High learning curve for using external solutions.
3.	No upgrade facility for major releases.
4.	Lack of management and monitoring tools capable of using PostgreSQL.
 
##Source
1.	http://en.wikipedia.org/wiki/PostgreSQL
2.	http://www.postgresql.org/about/advantages/
3.	http://www.slideshare.net/nikhilkadadi29/greatdebate-postgres-vs-mysql-presentation
<br></br>

#Redis
##Overview
Data structure server for advanced key-value cache and store.

##Advantage
1.	Open-source.
2.	Most popular key-value store.
3.	Value can contain complex data types with defined atomic operations.
4.	Achieves high write and read speed because it keeps all data in memory for quick access.

##Disadvantage
1.	No access control to configure server.
2.	Memory persistency affects performance.
##Source
1.	http://en.wikipedia.org/wiki/Redis
2.	http://redis.io/topics/faq
3.	http://www.quora.com/What-are-the-disadvantages-of-Redis
<br></br>

#SQLite
##Overview
RDBMS contained in a C programming library.

##Advantage
1.	Open-source.
2.	Serverless and integrated into application programs.
3.	No need for installation and configuration.
4.	Compact.
5.	ACID-compliant.
6.	Mostly support SQL standard.

##Disadvantage
1.	No user management.
2.	No way for manipulation to increase performance.

##Source
1.	http://en.wikipedia.org/wiki/SQLite
2.	https://www.sqlite.org/different.html
3.	https://www.digitalocean.com/community/tutorials/sqlite-vs-mysql-vs-postgresql-a-comparison-of-relational-database-management-systems
<br></br>

#Drizzle
##Overview
RDBMS forked from version 6.0 of MySQL, targeted for cloud service.

##Advantage
1.	Open-source.
2.	Smaller, slimmer, and fast than MySQL.

##Disadvantage
1.	Not very secure.

##Source
1.	http://en.wikipedia.org/wiki/Drizzle_(database_server)
2.	https://moodle.org/mod/forum/discuss.php?d=146977
<br></br>

AWS DynamoDB
##Overview
NoSQL database service offered as part of Amazon Web Service portfolio.

##Advantage
1.	Allows developers to purchase a service based on throughput rather than storage.

##Disadvantage
1.	Proprietary.
2.	Can only scale through request.

##Source
1.	http://en.wikipedia.org/wiki/Amazon_DynamoDB
<br></br>
