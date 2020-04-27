# differences_mysql-mongodb
La structure de mysql et mongo db sont différentes :
- mysql est une base de données relationelles (SGBDR) alors que MongoDB est NoSQL (base de donnée distribuée, non relationelle
- Dans une base de données mysql les informations sont stockées dans des tables alors pour une base de données MongoDB les tables sont représentées par des collections.

- Dans une base de données mysql une ligne(Row) est un élément horizontal dans une table représentant une énumération des valeurs. En mongoDb le concept row est représenté par un document.

- Dans une base de donnée MySQL une colonne est élément vertical dans une table représentant un ensemble de valeurs d'un attribut. En mongo db le concept column est représenté par le concept Field(un champ).

- Dans mysql nous avons la possibilité de faire des jointures entre plusieurs table tandis qu’en mongodb les liaisons entre les tables se font par une mise en relation ou linking .

- SQL est utilisé pour communiquer avec une base de données. C'est le seul langage de requête supporté par MySQL, enrichi de quelques extensions spécifiques aux fournisseurs. Malgré sa simplicité, SQL est un langage très puissant qui consiste essentiellement en deux parties: un langage de définition de données (DDL) et un langage de manipulation de données (DML). Alors que dans MongoDB, tout est un document, représenté comme un JSON.
MongoDB n'a pas de langage dédié pour gérer les documents et prend plutôt une approche très différente. La manipulation ou l'interrogation de document est décrite en utilisant un ensemble d'opérateurs très riches, composés l'un avec l'autre à l'aide de la structure JSON, comme tout autre document. Cette représentation unifiée est assez puissante, expressive et facile à comprendre, plus il n'a pas besoin d'apprendre un autre langage de programmation.
