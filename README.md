# Projet 1 : Portfolio Développeur

## Objectif
Créer un site vitrine moderne et minimaliste pour présenter un développeur et ses projets.  
Ce projet est réalisé en équipe avec GitHub en suivant un workflow collaboratif.

---

##  Structure des Pages
- `index.html` → Accueil
- `about.html` → À propos
- `skills.html` → Compétences
- `projects.html` → Projets
- `blog.html` → Blog
- `contact.html` → Contact

Chaque page possède son propre fichier CSS dédié (ex: `style-about.css`).

---

##  Charte Graphique
- **Couleur principale** : Bleu foncé `#1E3A5F`
- **Fond clair** : `#FOF4FF`
- **Accent bleu** : `#2563EB`
- **Texte secondaire** : `#64748B`
- **Typographie** :
  - Titres → Poppins 700
  - Corps → Inter 400
- **Style général** : Minimaliste, professionnel, avec beaucoup d’espace blanc.

---

# Organisation Git
- **main** → Code stable et validé (chef de groupe uniquement)
- **develop** → Branche d’intégration (tout le groupe)
- **feature-accueil** → Page d’accueil
  - `feature-accueil/feature-hero` → Section hero
  - `feature-accueil/feature-navbar` → Barre de navigation
  - `feature-accueil/feature-footer` → Footer (Zainab)
- **feature-projects** → Page projets
- **feature-contact** → Page contact

#  Rôles
- **Membre A** → Hero
- **Membre B** → Navbar
- **Membre C (Zainab)** → Footer
- **Membre D/E** → Composants projets

---

##  Workflow Git
1. Cloner le projet :  
   ```bash
   git clone [URL_DU_PROJET]
