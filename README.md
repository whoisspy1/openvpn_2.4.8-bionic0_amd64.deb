# XOR PATCH OBFUSCATEopenvpn_2.4.8-bionic0_amd64.deb

nano /etc/apt/sources.list
uncomment some sources with src mask
apt-get update && apt-get build-dep openvpn -y
wget --no-check-cert https://github.com/whoisspy1/openvpn_2.4.8-bionic0_amd64.deb
dpkg -i openvpn_2.4.8-bionic0_amd64.deb
wget https://git.io/v1jlQ -O openvpn-install.sh && bash openvpn-install.sh
nano /etc/openvpn/server.conf
management localhost 5555
scramble obfuscate YthCMgn24hny00nVXASDSChjGAJD231jszv/L21A
systemctl restart openvpn@server.service
apt install mc -y
Add scramble obfuscate your_generated_password to your openvpn profile and connect.
Profit!
