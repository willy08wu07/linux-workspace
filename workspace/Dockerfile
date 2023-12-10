FROM ubuntu:22.04

RUN useradd -u 1000 -g 100 -ms /bin/bash user
RUN apt update && \
    apt install -y vim autossh

USER user
