# serversetup

cd ~/code/
scp -r serversetup root@108.61.192.123:~/

On server

apt-get update
apt-get upgrade
cd /root/serversetup/ubuntu.20.04
chmod +x setup.sh
./setup.sh

when asked for ssh key, run the following command on the local machine
cat ~/.ssh/id_rsa.pub| pbcopy

