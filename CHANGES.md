Changes by Version
==================
Release Notes.

8.5.0
------------------
#### Project


#### Java Agent
* Remove invalid mysql configuration in agent.config.
* Add net.bytebuddy.agent.builder.AgentBuilder.RedefinitionStrategy.Listener to show detail message when redefine errors occur.
* Fix ClassCastException of log4j gRPC reporter.
* Fix NPE when Kafka reporter activated.
* Enhance gRPC log appender to allow layout pattern.
* Fix apm-dubbo-2.7.x-plugin memory leak due to some Dubbo RpcExceptions.
* Fix lettuce-5.x-plugin get null host in redis sentinel mode.
* Fix ClassCastException by making CallbackAdapterInterceptor to implement EnhancedInstance interface in the spring-kafka plugin.
* Fix NullPointerException with KafkaProducer.send(record).

#### OAP-Backend


#### UI


#### Documentation


All issues and pull requests are [here](https://github.com/apache/skywalking/milestone/76?closed=1)

------------------
Find change logs of all versions [here](changes).
