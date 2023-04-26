# 1. Convention de rédaction des commentaires liés aux commits

Date : 2023-04-26

## Contexte

Sur ce projet, il faut s'assurer que l'ensemble des personnes allant alimenter le répertoire utilisent les mêmes conventions de rédaction des commentaires des commits.

## Décision

Nous utiliserons la nomenclature issue de [**Conventional Commits**](https://www.conventionalcommits.org/en/v1.0.0/).
Il s'agit des bonnes pratiques liées à la gestion de code en ligne. La qualité des commits permet de se retrouver dans l'historique des commits et participe à une meilleure qualité de code.

## Structure d'un commentaire de commit

<type>[optional scope]: <description>

[optional body]

[optional footer(s)]

## Exemple d'utilisation du Conventional Commits

# Cas d'ajout ou modification d'une fonctionnalité

feat: commits qui ajoutent ou modifient une nouvelle fonctionnalité

# Cas de correction d'un bug

fix: commits servant à corriger une erreur

# Cas de gestion de la documentation

docs: commits qui affectent uniquement la documentation

# Cas de restructuration du code (refactoring)

refactor: commits qui restructurent le code sans changer son comportement
