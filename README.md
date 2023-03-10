# test
> **Disclaimer: This project is only for personal learning and communication, please do not use it for illegal purposes, please do not use it in a production environment**

xray panel supporting multi-protocol, **Multi-lang (English,Farsi,Chinese)**

# Install & Upgrade

```
bash <(curl -Ls https://raw.githubusercontent.com/wendyjorden/oldux/main/install.sh)
```

# SSL
```
apt-get install certbot -y
certbot certonly --standalone --agree-tos --register-unsafely-without-email -d yourdomain.com
certbot renew --dry-run
```

**If you think this project is helpful to you, you may wish to give a** :star2: 

# Default settings

- Port: 2053
- user: admin
- password: admin
- database path: /etc/x-ui/x-ui.db

before you set ssl on settings
- http:// ip or domain:2053/xui

After you set ssl on settings 
- https://yourdomain:2053/xui

**for enable traffic for users you should do :**

**xray Configuration :**
```json
  "policy": {
    "levels": {
      "0": {
        "statsUserUplink": true,
        "statsUserDownlink": true
      }
    },

    "system": {
      "statsInboundDownlink": true,
      "statsInboundUplink": true
    }
  },
  "routing": {
```

# suggestion system
- Ubuntu 20.04+

# pic

![1](https://raw.githubusercontent.com/MHSanaei/test/main/media/1.png)
![2](https://raw.githubusercontent.com/MHSanaei/test/main/media/2.png)
![3](https://raw.githubusercontent.com/MHSanaei/test/main/media/3.png)
![4](https://raw.githubusercontent.com/MHSanaei/test/main/media/4.png)

# a special thanks to
- [vaxilu](https://github.com/vaxilu/)
- [HexaSoftwareTech](https://github.com/HexaSoftwareTech/)
- [diditra](https://github.com/diditra/)
- [FranzKafkaYu](https://github.com/FranzKafkaYu)
- [alireza0](https://github.com/alireza0/)


## Stargazers over time

[![Stargazers over time](https://starchart.cc/MHSanaei/test.svg)](https://starchart.cc/MHSanaei/test)
