# XMMX BRIDGE RESOURCE v2.8

**Update v2.8 - 7/05/2026:**
```
• Improved framework detection so xmmx_bridge no longer mistakes QBX’s qb-core compatibility layer for the real qb-core resource.
• Updated bridge logic to use the detected framework consistently across client and server files.
• Fixed QBX servers incorrectly entering QBCore-only code paths, which caused nil QBCore errors.
• Restricted QB inventory adapters to only load when the actual detected framework is qb-core.
• Updated QBX consumable and duty/boss menu handling to use QBX exports instead of QBCore globals.
```

*Download the update from https://portal.cfx.re/assets/granted-assets*
