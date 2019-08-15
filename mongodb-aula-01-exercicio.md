# MongoDB - Aula 01 - Exercício
autor: Yago Augusto

## Importando os restaurantes

    ```
     ubuntu@ubuntu-Lenovo-B490:/data/db$ sudo mongoimport --db be-mean --collection restaurantes --drop --file restaurantes.json
2019-08-14T20:32:53.664-0300	connected to: localhost
2019-08-14T20:32:53.683-0300	dropping: be-mean.restaurantes
2019-08-14T20:32:55.290-0300	imported 25359 documents

    ```

## Contando os restaurantes

    ```
    > db.restaurantes.find({}).count()
25359


    ```
