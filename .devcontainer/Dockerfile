# Base image
FROM mcr.microsoft.com/devcontainers/base:bookworm

# Install Node + npm for Vue.js
RUN apt-get update && apt-get install -y nodejs npm

# Install Python + pip for Flask
RUN apt-get install -y python3 python3-pip

# Install Vue CLI globally
RUN npm install -g @vue/cli

# Install Flask
RUN pip3 install flask

# Default working directory
WORKDIR /workspace
