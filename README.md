[README (1).md](https://github.com/user-attachments/files/26774228/README.1.md)
# 🤙 ZePouce — Le partage sans blabla

![Version](https://img.shields.io/badge/version-1.0.0--beta-04b41f)
![Platform](https://img.shields.io/badge/platform-Android-04b41f)
![Built with](https://img.shields.io/badge/built%20with-FlutterFlow-blue)
![Backend](https://img.shields.io/badge/backend-Firebase-orange)
![RGPD](https://img.shields.io/badge/conformit%C3%A9-RGPD-04b41f)
![Langue](https://img.shields.io/badge/langue-Fran%C3%A7ais-blue)

> Application mobile de mise en relation entre auto-stoppeurs et conducteurs, pensée pour être simple, rapide et sans prise de tête.

---

## 📱 Aperçu

ZePouce connecte les personnes qui cherchent un trajet avec celles qui peuvent en proposer un — sans inscription complexe, sans frais, sans blabla.

L'application est actuellement en **version bêta** et disponible sur **Google Play Store** (France).

---

## ✨ Fonctionnalités

- 🗺️ **Trajets en temps réel** — publie ou trouve un trajet en quelques secondes
- 📍 **Géolocalisation intelligente** — GPS actif uniquement pendant un trajet
- 💬 **Messagerie intégrée** — communique directement avec le conducteur ou le passager
- ⭐ **Système d'avis** — note et consulte les profils pour voyager en confiance
- 🔒 **Sécurité & confidentialité** — conforme RGPD, données hébergées en Europe
- 🚩 **Signalement** — signale un comportement inapproprié en un tap

---

## 🛠️ Stack technique

| Composant | Technologie |
|---|---|
| Frontend | FlutterFlow (Flutter/Dart) |
| Backend | Firebase (Firestore, Auth, Storage) |
| Base de données | Cloud Firestore |
| Authentification | Firebase Authentication |
| Hébergement | Google Cloud (Europe) |
| CI/CD | GitHub |

---

## 🗂️ Structure de la base de données

```
Firestore/
├── users/          # Profils utilisateurs
├── trips/          # Trajets proposés
├── trajets/        # Trajets recherchés
├── messages/       # Messagerie entre utilisateurs
├── chat/           # Sessions de chat
├── ratings/        # Avis et notations
├── spots/          # Points de rendez-vous
├── spot_reviews/   # Avis sur les spots
└── reports/        # Signalements
```

---

## 🔒 Sécurité

ZePouce applique des règles strictes de sécurité Firebase :

- ✅ Chaque utilisateur ne peut modifier **que ses propres données**
- ✅ Les messages ne sont visibles que par les **deux participants**
- ✅ Les suppressions sont **désactivées** côté client
- ✅ Toutes les opérations requièrent une **authentification**
- ✅ Données GPS supprimées après chaque trajet

---

## 🇫🇷 Conformité RGPD

- Consentement explicite demandé au premier lancement
- Politique de confidentialité accessible depuis l'app
- Droit à l'effacement des données disponible
- Données hébergées en Europe (Google Cloud)
- Aucune revente de données à des tiers

---

## 🚀 Roadmap

### v1.0 — Lancement France *(en cours)*
- [x] Authentification utilisateur
- [x] Publication et recherche de trajets
- [x] Messagerie interne
- [x] Système d'avis
- [x] Conformité RGPD
- [x] Règles de sécurité Firebase
- [ ] Publication Google Play Store

### v1.1 — Améliorations
- [ ] Notifications push
- [ ] Vérification d'identité optionnelle
- [ ] Filtres de recherche avancés
- [ ] Mode sombre

### v2.0 — International
- [ ] Traduction en anglais
- [ ] Publication App Store (iOS)
- [ ] Expansion européenne

---

## 📸 Screenshots

*Coming soon — disponibles lors de la publication sur le Play Store*

---

## 🤝 Contribution

ZePouce est actuellement un projet personnel en phase bêta. Les contributions et retours sont les bienvenus !

1. Fork le projet
2. Crée une branche (`git checkout -b feature/amelioration`)
3. Commit tes changements (`git commit -m 'Ajout fonctionnalité X'`)
4. Push la branche (`git push origin feature/amelioration`)
5. Ouvre une Pull Request

---

## 📬 Contact

Pour toute question, suggestion ou signalement :
**[votre-email@zepouce.fr]**

---

## 📄 Licence

Ce projet est sous licence privée. Tous droits réservés © 2026 ZePouce.

---

<p align="center">
  Fait avec 🤙 en France
</p>
