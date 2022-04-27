# MyCaddy
build caddy server with my custom, include naiveproxy, trojan webdav and so on

xcaddy build \
          --with github.com/caddyserver/forwardproxy@caddy2=github.com/sagernet/forwardproxy@latest \
          --with github.com/mholt/caddy-webdav \
          --with github.com/mastercactapus/caddy2-proxyprotocol \
          --with github.com/kirsch33/realip \
          --with github.com/abiosoft/caddy-exec \
          --with github.com/greenpau/caddy-trace \
          --with github.com/aksdb/caddy-cgi/v2 \
          --with github.com/abiosoft/caddy-json-parse \
          --with github.com/caddyserver/ntlm-transport \
          --with github.com/mholt/caddy-l4 \
          --with github.com/sjtug/caddy2-filter \
          --with github.com/casbin/caddy-authz/v2 \
          --with github.com/imgk/caddy-trojan \
          --with github.com/caddyserver/transform-encoder
