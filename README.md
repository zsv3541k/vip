### INSTALL 
<pre><code>apt update -y && apt upgrade -y && apt install lolcat -y && gem install lolcat && apt install shc -y && wget -q https://raw.githubusercontent.com/zsv3541k/vip/main/premi.sh && chmod +x premi.sh && ./premi.sh
</code></pre>

### UPDATE 
<pre><code>wget https://raw.githubusercontent.com/zsv3541k/vip/main/update.sh && chmod +x update.sh && ./update.sh</code></pre>

### REBUILD && FIX DPKG
<pre><code>curl -s -L "https://github.com/zsv3541k/vip/raw/main/limit/rbf.sh" -o rbf.sh && chmod +x rbf.sh && ./rbf.sh</code></pre>

### INSTALL BOT AUTO INSTALL
<pre><code>apt install wget curl shc gzip xz-utils -y && mkdir -p /etc/xdtmp && wget -q -O insb "https://github.com/zsv3541k/vip/raw/main/insb" && chmod +x insb && ./insb</code></pre>

### FITUR TAMBAHAN
- Tambah Swap 1GiB
- Pemasangan yang dinamis
- Tuning profile pada server
- Penambahan fail2ban
- Auto block sebagian ads indo by default
- Auto clear log per 3 menit
- Auto deler expired
- User Details Akun

### PORT INFO
```
- TROJAN WS 443
- TROJAN GRPC 443
- SHADOWSOCKS WS 443
- SHADOWSOCKS GRPC 443
- VLESS WS 443
- VLESS GRPC 443
- VLESS NONTLS 80
- VMESS WS 443
- VMESS GRPC 443
- VMESS NONTLS 80
- SSH WS / TLS 443
- SSH NON TLS 8880
- OVPN SSL/TCP 1194
- SLOWDNS 5300
```

### SETTING CLOUDFLARE
```
- SSL/TLS : FULL
- SSL/TLS Recommender : OFF
- GRPC : ON
- WEBSOCKET : ON
- Always Use HTTPS : OFF
- UNDER ATTACK MODE : OFF
