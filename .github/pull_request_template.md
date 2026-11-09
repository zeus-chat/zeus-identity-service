## Cambio
<!-- Qué cambia y por qué (en español). El título del PR es un Conventional Commit en inglés: feat(HU-02): issue RS256 access tokens -->

## Historia
<!-- HU-xx · ADR-NNN -->

## Checklist (Definition of Done)
- [ ] Desarrollado con TDD (tests primero, el historial de commits lo evidencia)
- [ ] Los criterios de aceptación de la historia están cubiertos por tests (`@DisplayName("HU-xx: …")`)
- [ ] Los usuarios y claves de desarrollo no se cargan fuera de los perfiles `dev` y `staging`
- [ ] Ninguna contraseña ni clave privada en el repositorio (solo `.env.example`)
- [ ] Si cambia el flujo de autenticación: `07-api/authentication.md` en `zeus-chat-docs` actualizado
- [ ] Spotless y cobertura en verde (CI)
- [ ] Documentación afectada actualizada (README del servicio, ADR)
