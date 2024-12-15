---
Name: Roga Danar 'Kilo'
Edge: 3
Force: 2
Heart: 1
Iron: 2
Shadow: 2
Wits: 2
Health: 5
Spirit: 3
Supply: 5
Momentum: 6
Wealth: 0
Wounded: ⬡
Shaken: ⬡
Unprepared: ⬡
Harmed: ⬡
Traumatized: ⬡
Doomed: ⬡
Tormented: ⬡
Indebted: ⬡
XPSpent: 0
Bonds_Progress: 0
Bonds_TrackImage: "[[progress-track-0.svg]]"
Bonds_XPEarned: 0
Discoveries_Progress: 0
Discoveries_TrackImage: "[[progress-track-0.svg]]"
Discoveries_XPEarned: 0
Quests_Progress: 0
Quests_TrackImage: "[[progress-track-0.svg]]"
Quests_XPEarned: 0
Failures_Progress: 0
Failures_TrackImage: "[[progress-track-0.svg]]"
Failures_XPEarned: 0
---
# `=this.Name`
![|300](https://i.pinimg.com/originals/ff/a5/83/ffa583c1871bc725b0d214a48adaa5be.jpg)

## Stats
| Edge         | Force         | Heart         | Iron         | Shadow         | Wits         |
| ------------ | ------------- | ------------- | ------------ | -------------- | ------------ |
| `=this.Edge` | `=this.Force` | `=this.Heart` | `=this.Iron` | `=this.Shadow` | `=this.Wits` |

## Meters
| Health | Spirit | Supply | Wealth | Momentum |
| --- | --- | --- | --- | --- |
| `=this.Health` | `=this.Spirit` | `=this.Supply` | `=this.Wealth` | `=this.Momentum` |

## Impacts
| Misfortunes | Lasting Effects | Burdens |
| --- | --- | --- |
| `=this.Wounded` Wounded | `=this.Harmed` Permanently Harmed | `=this.Doomed` Doomed |
| `=this.Shaken` Shaken | `=this.Traumatized` Traumatized | `=this.Tormented` Tormented |
| `=this.Unprepared` Unprepared |  | `=this.Indebted` Indebted |

## Legacies
| XP Earned | XP Spent |
| --- | --- |
| `=this.Bonds_XPEarned+this.Discoveries_XPEarned+this.Quests_XPEarned` | `=this.XPSpent` |
### Bonds (Rolled Over? `=choice(this.Bonds_Progress > 40, "Yes", "No")`)
```dataview
LIST without id embed(link(meta(Bonds_TrackImage).path, "350"))
WHERE contains(file.path, this.file.path)
```
### Discoveries (Rolled Over? `=choice(this.Discoveries_Progress > 40, "Yes", "No")`)
```dataview
LIST without id embed(link(meta(Discoveries_TrackImage).path, "350"))
WHERE contains(file.path, this.file.path)
```
### Quests (Rolled Over? `=choice(this.Quests_Progress > 40, "Yes", "No")`)
```dataview
LIST without id embed(link(meta(Quests_TrackImage).path, "350"))
WHERE contains(file.path, this.file.path)
```
### Failures (Rolled Over? `=choice(this.Failures_Progress > 40, "Yes", "No")`)
```dataview
LIST without id embed(link(meta(Failures_TrackImage).path, "350"))
WHERE contains(file.path, this.file.path)
```
## Vows / Progress Tracks
```dataview
TABLE Name, embed(link(meta(TrackImage).path, "150")) AS Progress
FROM #incomplete WHERE file.name != "Progress_Template" 
```
## Assets
Force Sensitive is a free Asset

> [!note]- Force Sensitive
> ![[Force/Force_Sensitive]]

Roga is allowed 2 Force abilities

> [!NOTE]- Force Shroud
> ![[Force_Shroud]]

> [!NOTE]- Force Precog
> ![[Force _Precog]]

Roga is allowed three Assets

> [!NOTE]- Infiltrator
> ![[Infiltrator]]

> [!NOTE]- Jedi Padawan
> ![[Jedi_Padawan]]

> [!NOTE]- Jedi Master Companion
> ![[Jedi_Master_Companion]]



## Description



## History

Roga Danar, known by his codename 'Kilo', is a Force-sensitive human male who has walked a unique path within the Jedi Order. His journey began under the tutelage of Jedi Master Alara Ven, who provided him with formal training as her Padawan. Master Ven instilled in Roga the core principles of the Jedi, emphasizing discipline, wisdom, and the importance of the Jedi Code. Their missions before the Clone Wars were marked by a blend of diplomacy and combat, shaping Roga into a well-rounded Jedi Knight.

However, Roga's path diverged at the beginning of the Clone Wars, when he was selected by the Jedi Council for specialized training under the enigmatic Jedi Master Kael Zaryn, a renowned spy master within the Order. Under Master Zaryn's guidance, Roga honed his skills in black ops, learning the arts of stealth, espionage, and psychological operations. This clandestine training was kept secret from most of the Jedi Order, as it involved techniques and missions that operated in the shadows, often blurring the lines of traditional Jedi conduct.

Roga's dual training allowed him to excel in both conventional and covert operations, making him a versatile and invaluable asset. Despite the secrecy surrounding his black ops missions, Roga remained fiercely loyal to his mentors and the Jedi Order, often grappling with the internal conflict between his covert duties and the Jedi Code.

The issuance of Order 66 forced Roga into hiding, changing his name to Dellum Elsh. He struggles to reconcile his past with the new reality of a galaxy without the Jedi Order. His skills in disguise and deception have kept him safe, but the weight of his secretive past continues to haunt him as he navigates a world where the Jedi are hunted and hope is scarce.

---
