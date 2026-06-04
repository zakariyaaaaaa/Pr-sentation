<div align="center">

<img src="https://go.dev/blog/go-brand/Go-Logo/PNG/Go-Logo_Blue.png" alt="Go Logo" width="120"/>

# 🚀 Go (Golang) — Présentation

> **Langage de programmation moderne, rapide et efficace**  
> Créé par Google · Open Source · Depuis 2009

[![Made with Go](https://img.shields.io/badge/Made%20with-Go-00ACD7?style=for-the-badge&logo=go&logoColor=white)](https://golang.org)
[![Open Source](https://img.shields.io/badge/Open-Source-22C55E?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](https://github.com)
[![Google](https://img.shields.io/badge/Created%20by-Google-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://google.com)
[![Presentation](https://img.shields.io/badge/Slides-10%20Slides-FF6B6B?style=for-the-badge&logo=microsoftpowerpoint&logoColor=white)](#)

</div>

---

## 📋 Table des Matières

- [🎯 À propos](#-à-propos)
- [👨‍💻 Créateurs](#-créateurs)
- [⚡ Caractéristiques](#-caractéristiques)
- [💻 Hello World](#-hello-world)
- [✅ Avantages](#-avantages)
- [❌ Inconvénients](#-inconvénients)
- [🌐 Domaines d'utilisation](#-domaines-dutilisation)
- [🏢 Entreprises](#-entreprises-utilisant-go)
- [📊 Contenu de la Présentation](#-contenu-de-la-présentation)
- [👤 Auteur](#-auteur)

---

## 🎯 À propos

Cette présentation couvre les **fondamentaux du langage Go (Golang)**, conçu par Google pour allier la **rapidité du C** à la **simplicité de Python**.

```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World! 👋")
}
```

> **Résultat :** `Hello, World! 👋`

---

## 👨‍💻 Créateurs

| 👤 Nom | 🔧 Rôle |
|--------|---------|
| **Robert Griesemer** | Compilateur & Runtime |
| **Rob Pike** | Plan 9 & Unix expert |
| **Ken Thompson** | Co-créateur d'Unix & C |

> 🎯 **Objectif :** Créer un langage aussi rapide que C, aussi simple que Python.

---

## ⚡ Caractéristiques

```
✏️  Syntaxe simple       →  Facile à lire et à maintenir
⚡  Compilation rapide   →  Build en quelques secondes
🧹  Garbage Collector    →  Gestion mémoire automatique
🔀  Goroutines           →  Concurrency native et légère
🌍  Multi-plateforme     →  Linux, Mac, Windows...
🔒  Typage statique      →  Erreurs détectées à la compilation
```

---

## 💻 Hello World

```go
package main          // 1️⃣ Point d'entrée du programme

import "fmt"          // 2️⃣ Import de la bibliothèque de formatage

func main() {         // 3️⃣ Fonction principale (obligatoire)
    fmt.Println("Hello, World!")  // 4️⃣ Affiche du texte dans la console
}
```

**Compiler & Exécuter :**
```bash
go run main.go
# Hello, World!
```

---

## ✅ Avantages

- 🎓 **Facile à apprendre** — Syntaxe minimaliste, courbe d'apprentissage douce
- 🚀 **Très rapide** — Performances proches du C/C++ grâce à la compilation native
- 🔒 **Sécurisé** — Gestion mémoire sûre, pas de pointeurs dangereux
- 🌐 **Open Source** — Communauté active, millions de packages sur [pkg.go.dev](https://pkg.go.dev)
- 🌍 **Excellent pour le Web** — Parfait pour les APIs REST, microservices et cloud

---

## ❌ Inconvénients

- 📦 **Bibliothèques limitées** — Écosystème plus petit que JavaScript ou Python
- 🔁 **Gestion d'erreurs répétitive** — Le pattern `if err != nil` revient souvent
- 🖥️ **Interfaces graphiques limitées** — Pas de framework GUI natif de référence

---

## 🌐 Domaines d'utilisation

<div align="center">

| 🌐 Web | 🔌 APIs | ☁️ Cloud | 🧩 Microservices | ⚙️ DevOps | 🔗 Réseaux |
|--------|---------|----------|-----------------|----------|-----------|
| ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |

</div>

---

## 🏢 Entreprises Utilisant Go

<div align="center">

| 🏢 Entreprise | 🎯 Utilisation |
|--------------|---------------|
| 🔵 **Google** | Créateur et utilisateur principal |
| 🐳 **Docker** | Plateforme de conteneurisation |
| 🚗 **Uber** | Microservices haute performance |
| 📦 **Dropbox** | Migration Python → Go pour les perfs |
| 🎮 **Twitch** | Streaming vidéo à grande échelle |

</div>

> 💡 **Pourquoi Go ?** Pour sa rapidité d'exécution, sa simplicité opérationnelle et son excellente gestion de la concurrence à grande échelle.

---

## 📊 Contenu de la Présentation

| # | 📑 Slide | 📝 Contenu |
|---|---------|-----------|
| 1 | 🎯 Titre | Introduction au langage Go |
| 2 | 📖 Introduction | C'est quoi Go ? |
| 3 | 👨‍💻 Créateurs | Robert Griesemer, Rob Pike, Ken Thompson |
| 4 | ⚡ Caractéristiques | Les 6 points clés |
| 5 | 💻 Code | Structure d'un programme Go |
| 6 | ✅ Avantages | Les 5 avantages majeurs |
| 7 | ❌ Inconvénients | Les 3 limites du langage |
| 8 | 🌐 Domaines | 6 domaines d'application |
| 9 | 🏢 Entreprises | Les 5 géants qui utilisent Go |
| 10 | 🏁 Conclusion | Résumé & message final |

---

## 🛠️ Ressources Utiles

| 🔗 Lien | 📝 Description |
|--------|---------------|
| [golang.org](https://golang.org) | Site officiel de Go |
| [pkg.go.dev](https://pkg.go.dev) | Documentation & packages |
| [go.dev/play](https://go.dev/play) | Playground Go en ligne |
| [github.com/golang/go](https://github.com/golang/go) | Code source officiel |

---

## 👤 Auteur

<div align="center">

**Smitek**  

[![GitHub](https://img.shields.io/badge/GitHub-Smitek-181717?style=for-the-badge&logo=github)](https://github.com)

---

*Go est un excellent choix pour développer des applications rapides et robustes. 🚀*

**Merci pour votre attention ! 😊**

</div>
