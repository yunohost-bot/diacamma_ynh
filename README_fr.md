<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Diacamma pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/diacamma.svg)](https://dash.yunohost.org/appci/app/diacamma) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/diacamma.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/diacamma.maintain.svg)

[![Installer Diacamma avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=diacamma)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Diacamma rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

# Présentation de Diacamma

_Diacamma_ est un ensemble de logiciels libres et gratuits de gestion administrative et financière imaginé et développé pour les bénévoles.

## Diacamma Asso

**Gérer simplement les adhésions à votre association**

_Diacamma Asso_ vous permet de classer facilement vos adhérents présents et passés.

 * Avoir la liste de vos adhérents avec toutes leurs coordonnées.
 * Gérer leurs cotisations par activités et catégories.
 * Gérer facilement les événements de votre association (examens, stages, sorties, ...).
 * Gérer le stock de votre centrale d'achat associative.
 * Lier une facture à vos cotisations et vos événements.

 
## Diacamma Syndic

**Suivez la situation de votre copropriété**

_Diacamma Syndic_ permet aux syndics bénévoles de gérer simplement leur copropriété.

 * Tenir une comptabilité en conformité avec la réglementation française des copropriétés.
 * Suivre la situation de chaques copropriétaires.
 * Créer et envoyer des appels de fonds.
 * Ventiler les dépenses de la copropriété sur chacun en fonction de ses tantièmes.


**Version incluse :** 23.12.18.10~ynh1

**Démo :** <https://asso.diacamma.org>

## Captures d’écran

![Capture d’écran de Diacamma](./doc/screenshots/03_bilan_comptable.png)
![Capture d’écran de Diacamma](./doc/screenshots/01_fiche_adherent.png)
![Capture d’écran de Diacamma](./doc/screenshots/02_situation_coporprietaire.png)

## Documentations et ressources

- Site officiel de l’app : <https://www.diacamma.org>
- Documentation officielle de l’admin : <https://asso.diacamma.org/Docs>
- Dépôt de code officiel de l’app : <https://github.com/Diacamma2>
- YunoHost Store : <https://apps.yunohost.org/app/diacamma>
- Signaler un bug : <https://github.com/YunoHost-Apps/diacamma_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/diacamma_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/diacamma_ynh/tree/testing --debug
ou
sudo yunohost app upgrade diacamma -u https://github.com/YunoHost-Apps/diacamma_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
