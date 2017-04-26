# Seedbox-Compose
A docker-compose file to deploy complete Seedbox based only Docker. Install a fresh Debian / Ubuntu Server, install git git-core and docker and use this **Docker-compose.yml** to deploy your Seedbox.

## Services availables in this docker-compose

Service | Port | Description | Link
------------ | ------------- | ------------- | ------------- |
Nginx | 80, 443 | .. | https://nginx.org
Fail2Ban | -- | .. | ..
MariaDB | 3306 | .. | ..
Nextcloud | 8181 | Self-hosted cloud Service | https://nextcloud.com
Rtorrent/RuTorrent | 8282, 49160, 49161 | ... | ...

  * [https://www.nginx.com/|**Nginx**] : 80, 443
  * **Fail2Ban**
  * **MariaDB**
  * **Nextcloud** : 8181 - IP-ADDRESS/nextcloud
  * **Rutorrent** : 8282 - IP-ADDRESS/rutorrent
  * **Jackett** : 8383 - IP-ADDRESS/jackett
  * **Radarr** : 8484 - IP-ADDRESS/radarr
  * **Sonarr** : 8585 - IP-ADDRESS/sonarr
  * **UI For Docker** : 8686 - IP-ADDRESS/uifordocker
  * **Plex Media Server** : 32400 - IP-ADDRESS:32400/web
  * **PlexPy** : 8787 - IP-ADDRESS/plexpy
