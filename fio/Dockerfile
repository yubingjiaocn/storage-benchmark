FROM ubuntu:22.04
RUN apt-get update -y && apt-get install -y fio && apt-get clean && rm -rf /var/lib/apt/lists/*
ADD task.fio /root/
CMD ["/bin/sh", "-c", "fio", "/root/task.fio"]