# Получение данных из RabbitMQ в Yandex Managed Service for ClickHouse®

В кластер [Managed Service for ClickHouse®](https://yandex.cloud/ru/docs/managed-clickhouse) вы можете поставлять данные из брокера сообщений RabbitMQ в реальном времени. Managed Service for ClickHouse® будет автоматически вставлять данные в таблицу на [движке RabbitMQ](https://clickhouse.com/docs/ru/engines/table-engines/integrations/rabbitmq). Подготовка инфраструктуры для виртуальной машины и Managed Service for ClickHouse® через Terraform описана в [практическом руководстве](https://yandex.cloud/ru/docs/tutorials/dataplatform/fetch-data-from-rabbitmq), необходимый для настройки конфигурационный файл [clickhouse-cluster-and-vm-for-rabbitmq.tf](clickhouse-cluster-and-vm-for-rabbitmq.tf) расположен в этом репозитории.
