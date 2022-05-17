# Домашнее задание к занятию "08.03 Использование Yandex Cloud"

1. Playbook описывает процесс устанвоки СУБД clickhouse, lighthouse и агентов vector для CentOS.
2. В inventory созданы 3 группы устройств: clickhouse (192.168.1.90),lighthouse (192.168.1.126), Version (192.168.1.56).
3. В переменных средах для всех устройств указана версия vector (vector_version). Для группы clickhouse указанны: IP адрес сервера СУБД (clickhouse_server), версии ПО (clickhouse_version) и намиенование пакетов (clickhouse clickhouse_packages)
4. В шаблонах находятся: vector.toml - конфиг vector. default.conf - конфиг nginx для lighthouse. config.xml - конфиг clickhouse.
