# docker-influxdb-mariadb-grafana
Simple Docker + InfluxDB + MariaDB + Grafana docker-file


# Installing

## Requirements
```
linux
docker
docker-compose
reading ability
basic docker-compose knowledge and the layout
```


# Setup
You will need some basic understanding of how docker-compose works, as well as basic linux skills.

## Environment Variables:
### MariaDB:
```
MYSQL_PASSWORD
```

### InfluxDB:
```
INFLUXDB_ADMIN_USER
INFLUXDB_ADMIN_PASSWORD
INFLUXDB_WRITE_USER
INFLUXDB_WRITE_USER_PASSWORD
```

### Grafana:
```
GF_SERVER_DOMAIN
GF_SERVER_ROOT_URL
GF_SECURITY_ADMIN_PASSWORD
GF_DATABASE_PASSWORD
```

## Paths:
Assumes you have `/data` configured on your system -- use whatever you like, that's just my preference.

### Mariadb:
```
/data/mysql/grafana
```

### InfluxDB:
```
/data/influxdb/data
```

### Grafana:
```
/data/grafana/plugins
```
