# Systemadmin-Work

1. Day 1:
    - Einrichtung von SSH mit deaktiviertem Root-Login  
    - Konfiguration der Firewall mit UFW und iptables  
    - Erstellung von Benutzern, Zuweisung zu Gruppen und Anpassung der sudoers-Berechtigungen
      
2. Day 2:
    - Eine externe Festplatte für Backups einrichten, indem eine Partition erstellt, formatiert und eingebunden wird.
    - LVM: Ein Physical Volume wurde erstellt, einer Volume Group hinzugefügt, ein Logical Volume angelegt und der Speicher flexibel erweitert.
    - Datenübertragung mit rsync unter Beibehaltung der Berechtigungen und Sicherung über SSH

3. Day 3:
    - Installation von Nginx
    - Erstellen einer HTML-Seite und das Konfigurieren eines Proxy-Servers
    - ein SSL-Zertifikat mit Certbot für HTTPS eingerichtet.
      
4. Day 4:
    - Erstellung eines Skripts zur Sammlung von Systeminformationen
    - Erstellung einer systemd-Dienstdatei und eines Timers, um das Skript alle 30 Minuten auszuführen
    - Aktivierung und Start des Timers, sowie Überprüfung des Log-Files mit tail

      
5. Day 5:
    - Konfiguration von iptables für SSH, HTTP und HTTPS, Blockierung anderer Verbindungen.
    - Protokollierung abgelehnter Pakete mit LOG.
    - Erfassung von HTTP-Verkehr auf Port 22 mit tcpdump.
    - Installation und Einrichtung von OpenVPN für VPN-Verbindungen.
      
6. Day 6: Überwachungs- und Performance-Tools
    - Nagios: Überwacht Prozesse und Ressourcen wie CPU und Speicher.
    - htop: Zeigt Prozesse und Systemressourcen in Echtzeit an.
    - iotop: Überwacht Festplatten-I/O und zeigt die größten Datenverbraucher.
    - Bash-Skript: Sammelt stündlich Leistungsdaten und versendet sie per E-Mail.
      
7. Day 7:
    Sicherheits-Tools für Serversicherheit:
    - Fail2Ban: schützt SSH, Apache & Nginx vor Brute-Force-Angriffen
    - Lynis: analysiert das System auf Sicherheitslücken.
    - GPG: verschlüsselt Dateien für mehr Datenschutz.

