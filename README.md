## Docker install instructions
 - https://docs.docker.com/install/linux/docker-ce/ubuntu/
 - If you are running disco, make sure to set to bionic
 -  sudo usermod -aG docker $USER

## Install Yarn
  - https://yarnpkg.com/lang/en/docs/install/#debian-stable
  - sudo apt-get update && sudo apt-get install yarn

## Prepare for Elasticsearch
  - Run the following command:
  ```sudo sysctl -w vm.max_map_count=262144```
