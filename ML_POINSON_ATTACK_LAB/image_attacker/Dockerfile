FROM ubuntu:20.04

ARG DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt-get install -y --no-install-recommends python3 python3-pip git
RUN git clone https://github.com/wonkr/CIS700_project.git

COPY start.sh /start.sh
RUN chmod +x /start.sh
CMD ["/start.sh"]

