# ec2-multiple-ips

Multiple ips proxy on Amazon
1. add network interface
2. add private ips on this network interface
3. add elastik ips
4. attach elastik ip to private ip, 1 private ip - 1 elastic ip
5. om linux add new virtual network interface with private ip

Install proxy, for example Squid
—
Config: /etc/squid/squid.conf
