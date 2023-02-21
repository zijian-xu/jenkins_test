FROM centos/python-38-centos7:latest

RUN pip install --upgrade pip && \ 
    pip install pandas boto3 pymysql slack_sdk

WORKDIR /opt/app-root/src

CMD "/bin/bash"