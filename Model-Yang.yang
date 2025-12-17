module simple-system {
  // Préfixe et namespace
  namespace "urn:example:simple-system";
  prefix "sys";

  // Métadonnées
  organization "Demo Lab";
  description
    "Un modèle YANG très simple pour la démo.";

  // Le 'container' est notre structure principale
  container system {
    description "Contient la configuration de base du système.";

    // Les 'leaf' sont les points de données réels
    leaf hostname {
      type string;
      description "Le nom d'hôte de l'appareil.";
    }

    leaf domain-name {
      type string;
      description "Le nom de domaine de l'appareil.";
    }
  }
}
