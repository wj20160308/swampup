FROM 127.0.0.1:8081/docker/docker-framework:latest

MAINTAINER Wangjin Wangjin wangjinrj@inspur.com

ADD war/*.war /home/exec/tomcat/webapps/swampup.war

CMD /bin/bash -c cd /home/exec; /home/exec/tomcat/bin/catalina.sh run

