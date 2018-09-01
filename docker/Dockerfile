# from base image centos
FROM centos
MAINTAINER JimWu
#install java
RUN yum -y install java
#inatall app
#ADD <src> <dest> from appUrl to container destUrl
ADD docker-demo.tar /app.jar
#start app
ENTRYPOINT ["java" ,"-jar","/app.jar"]