RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://你的帳號名稱.github.io/你的repository名稱/index.html$1 [R,L]
