## Patched SQLibrary for PaperMC 1.16+

This is an updated drop-in replacement for SQLibrary 7.1 which should fix class loading / connection issues introduced by [renamed classes in the mysql-connector-java dependency of PaperMC](https://github.com/PaperMC/Paper/pull/5474).

__Important for developers:__
It is strongly suggested to remove this library from your dependencies and use [Bukkit's plugin database API instead](https://bukkit.fandom.com/wiki/Plugin_Databases) instead!
