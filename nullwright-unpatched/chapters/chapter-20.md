# Chapter 20 — Supply Chain Rebellion

Sable removed the tracking marker on the second day.

I'm going to skip the details because they involved a back-alley signal weaver with tattoos on her teeth, a ceramic bowl full of something that smelled like burnt hair and ethical compromise, and forty-five minutes of pain that made the Null Anchor overload feel like a firm handshake. When it was over, I lay on a cellar floor staring at a water stain on the ceiling and discovered that the stain looked exactly like the goddess relief from Kiosk Seventeen, which was either a sign from the divine or evidence that I was concussed.

"Tag's dead," Sable confirmed, checking his signal lens. "Arbiter-grade, though. Impressive craftsmanship. I almost feel bad destroying it."

"Your sympathy is noted."

"I said almost."

So: no more tracking pulse. Still no Null Anchor, no Thread reserves, and a nervous system that felt like it had been rewired by an enthusiastic amateur. But at least Halden couldn't follow me by satellite anymore.

Small victories. The currency of people who can't afford large ones.

---

Hobb called the meeting on the third day, in the basement of a laundry that backed onto the Ledger Guard barracks.

The laundry was run by Mira Dessk, a woman shaped like a barrel with opinions shaped like bludgeons, who had agreed to host resistance planning sessions in exchange for—and this is a direct quote—"the privilege of inconveniencing those bastards through every wall they share with my boilers." She'd been overcharged on water tariffs for six years. The Quiet Audit evidence had confirmed her suspicion that the tariff was punitive retaliation for a complaint she'd filed. Mira's anger had the patient quality of something aged in oak.

The basement smelled like soap and revolution, which is not as incompatible as you'd think.

Hobb stood at a makeshift table covered in hand-drawn maps and inventory lists. Around him: Nia, Ilya (recovered from System sleep, quietly furious about it), Sable, and six of Hobb's network leaders—shopkeepers, a canal supervisor, and the retired printer named Wullen who had ink permanently embedded in the creases of his hands.

"The protests worked," Hobb said, in the tone of a man who considered that the easy part. "Concordance knows we have public sympathy. They've responded with containment—barricades, curfews, increased patrols. Expected. But they've also done something smarter."

He tapped the map. "Ration adjustments. Starting yesterday, District Nine's supply allocations were reduced by fifteen percent. Officially, it's a 'redistribution to address city-wide shortfalls.' Unofficially—"

"It's punishment," Mira said.

"It's leverage. They're squeezing the district's supply chain to turn civilian discomfort into civilian resentment. If people start going hungry, they blame the protests. They blame us. Concordance doesn't need to beat us. They need us to beat ourselves."

I'd seen this before. Not personally—I was seventeen and my geopolitical experience was limited to grocery theft—but Hobb had explained the playbook. Cut supplies. Wait. Let hunger do the enforcement. When people are choosing between feeding their kids and supporting a movement, the kids win. Always. As they should.

"So we fix the supply chain," I said.

Everyone looked at me. Hobb's look said *I was getting there.* Nia's look said *let the adults talk.* Ilya's look was calculating.

"That's why we're here," Hobb said, with the generosity of a teacher who lets the student think they contributed. "I've been mapping alternative supply routes for the last forty-eight hours. Canal district has three unofficial intake points that bypass the Concordance allocation stations. The Ragline can move goods through the underworks. And there are Freehold suppliers willing to sell at cost if we can guarantee safe transport."

"The problem," Nia said, "is the corridors."

She unrolled her own map—a courier's map, routes marked in shorthand that only runners could read. "Concordance has increased patrols on every known underworks access point. The main supply corridors are choked. I can move small packages through shadow routes, but bulk goods—food, medicine, lamp oil—need wider channels."

"Which are watched."

"Which are watched."

Silence.

Hobb looked at me. The look was careful, measuring, the look of a man who didn't want to ask what he was about to ask because he knew the cost.

"Can you clear corridors?"

I knew what he meant. Use Fault-Sight to find surveillance gaps. Use exploits to disable monitoring nodes. Use Thread to create safe passages.

Three days ago, I could have done it at scale. Three days ago I had a Null Anchor as safety net, full Thread reserves, and the confidence that came from knowing I could always escape if things went sideways.

Now I had twelve Thread, severe neural fatigue, no fallback, and a System that had specifically patched against my signature's causal exploit methods.

"I can do small things," I said.

"Define small."

"Individual monitoring nodes. One at a time. Low-level faults—pressure variance, timing desync. Nothing that requires complex chaining or heavy Thread. The kind of exploits that look like maintenance errors instead of sabotage."

"How small?"

"Enough to open a corridor for maybe twenty minutes before the fault self-corrects. One corridor at a time. And I'll need to space them out—two, three per day maximum, or the signature accumulation triggers a pattern match."

Hobb's expression said this was not what he'd hoped for. It was also not nothing.

"What about the relational faults?" Ilya asked. "The connection-type exploits from the Freeholds. Those don't match your standard signature."

"They also require Thread I don't have right now. Relational exploits are expensive. Individual node disruptions are cheap." I spread my hands. "I'm shopping on a budget."

Nia studied her map. "Three per day. Twenty-minute windows. If I pre-stage courier teams at each corridor, we can move significant volume in twenty minutes. Dashel's crew alone can carry two hundred pounds in that window if they know the route."

"It's not enough to replace the full supply allocation," Hobb said.

"It doesn't need to be. The protests showed people the *why*. The supply runs show them the *how*. If we can distribute even half the shortfall through alternative channels, the Concordance squeeze fails. People see that resistance has logistics, not just anger."

"And the Concordance sees that we're organized," Sable added, "which makes us a real problem instead of a symbolic one."

"That cuts both ways."

"Everything cuts both ways. That's what cutting means."

---

We started that night.

The first corridor was a service tunnel beneath the canal market, monitored by a resonance detector and two ward emitters. I spent forty minutes crouched in a maintenance alcove, mapping the monitoring setup through Fault-Sight while trying not to think about how exposed I was without an anchor.

The resonance detector ran on a six-second sweep cycle. At the peak of each cycle, there was a natural desync where the detector's calibration marginally exceeded the ward emitters' response time—a fault so small it was invisible to normal observation. I wouldn't have seen it a month ago. Ilya's training, the diagnostic lens, and five months of survival education had sharpened my sight to the point where I could read the spaces between heartbeats.

I reached with Thread. Not much—a whisper. Questioned the timing desync. Not broke it—*expanded* it. Asked the gap between the detector's peak and the ward's response to consider being slightly larger than specification.

It considered.

**EXPLOIT: Timing Variance Extension**
**Target: Monitoring Node C-14 (Canal Market Sub-Level)**
**Method: Resonance Desync Amplification**
**Duration: ~22 minutes**
**Signature: Minimal (within maintenance tolerance)**
**Thread cost: 1**

One Thread. The cheapest exploit I'd done since learning what Thread was. And it opened a window.

Nia's team moved through the corridor like shadows with shopping bags. Rice. Dried fish. Lamp oil. Bandages. The essentials that the Concordance had cut to fifteen percent, packed into courier bags and distributed through Hobb's shopkeeper network before dawn.

Nobody got caught.

Nobody got hurt.

Nobody gained a level.

---

We did it again the next day. Different corridor. Different monitoring setup. Same principle: find the smallest possible fault, expand it the cheapest possible way, hold the window while people moved goods that other people needed to survive.

And the day after that.

And the day after that.

On the fourth day, a woman I didn't know stopped me on a stairwell in the underworks. She was carrying a sack of flour on one shoulder and a sleeping toddler on the other. She looked at me—really looked, past the grime and the exhaustion and the seventeen-year-old face that probably didn't match whatever legend she'd heard—and said, "You're him."

"Depends on who 'him' is."

"The one opening the corridors."

"I'm one of many."

She shifted the toddler higher. "My neighbor said you could walk through walls and turn Arbiters inside out."

"Your neighbor has a generous imagination."

"Can you walk through walls?"

"Only the ones with plumbing problems."

She laughed—surprised, like she'd forgotten that was something people did—and went on her way, flour and child and all.

Nia found me staring after her.

"You're doing that thing," she said.

"What thing?"

"The thing where you think about the weight of responsibility until your face looks like Hobb's."

"I don't look like Hobb."

"You're getting there."

---

The supply runs weren't glamorous. They weren't the kind of exploit-chain, Thread-burning, reality-bending operations that made Fault-Sight sing and the System sit up and take notice. They were small. Mundane. Repetitive. I opened corridors. Nia's couriers moved goods. Hobb's shopkeepers distributed. Mira's laundry served as a hub because the Ledger Guard next door never noticed that the building's foot traffic had tripled.

I leveled once. In six days.

**LEVEL UP: 14 → 15**
**Progression source: Sustained low-variance civilian support operations**
**Thread recovery: Partial (12 → 14)**
**Note: Growth rate below class average for level bracket. Null Anchor loss has reduced exploit diversity. Current progression model favors caution over innovation.**

Growth rate below class average. I was leveling slower than a Nullwright should because I was using exploits for twenty-minute supply corridors instead of pushing into deeper faults, higher-risk chains, more complex interactions. The kind of growth that had taken me from Level 8 to Level 14 in the Freeholds—chaining through relic vaults, contact with the Custodian, combat synergy with Nia—was on hold.

I was getting weaker. Relatively. The System was designed to reward escalation. Big risks, big gains. Small risks, small gains. And the Concordance was escalating whether I was or not.

Ilya noticed. Because Ilya noticed everything that involved Thread math.

"Your growth curve is flattening," she said on the fifth evening, studying my status pane with the clinical attention she reserved for things that worried her. "At this rate, you'll reach Level 16 in another two weeks. A month ago, you were gaining a level every three days."

"A month ago, I was raiding archives and fighting bounty hunters."

"Yes. And growing proportionally. The System rewards variance—novel interactions, complex exploits, high-risk decisions. What you're doing now—"

"Is keeping people fed."

"—is operationally valuable and progressionally stagnant."

I let the silence sit.

"You think I should be pushing harder," I said.

"I think you should be aware of the tradeoff. Halden is not slowing down. The Concordance is not flattening its curve. If you reach the next confrontation at Level 16 with depleted Thread and a cautious exploit profile, while they've spent the interval hardening their response architecture—"

"Then I lose."

"Then the gap that was already significant becomes insurmountable."

She was right. I knew she was right. The math didn't lie, and Ilya was always the math.

But.

On the sixth day, Hobb reported that supply distribution had reached seventy percent of pre-squeeze levels. Seventy percent. The Concordance had cut fifteen percent, and we'd replaced more than the shortfall through courier runs, shopkeeper networks, and twenty-minute windows held open by exploits so small the System classified them as maintenance errors.

Wullen's printing press had produced two thousand copies of the Quiet Audit evidence in broadsheet format, distributed through the bread-and-laundry network. Protests had spread to three more districts. A guild journeyman in District Seven had publicly challenged his master's class-right claim, citing specific evidence from the broadsheets. A Ledger Guard clerk had anonymously delivered internal memos confirming the ration reduction was punitive.

The movement was growing. Not because of me—because of Hobb's logistics, Nia's routes, Mira's laundry, Wullen's press, Tallen's bread deliveries, Drassa's candles burning in windows as silent signals, Resk's hardware shop taking messages, Dashel's couriers running goods through dark corridors at three in the morning.

I was the exploit. They were the operation.

And the operation was winning in ways that didn't show up on a status pane.

"Ilya," I said. "Do you know what Hobb told me when we re-entered Veyrun?"

"Something disparaging about your work ethic, probably."

"He said infrastructure is power. He was right. Not because infrastructure fights—because infrastructure *feeds*. And fed people fight differently than hungry ones."

She looked at me for a long time.

"You're making a choice," she said. "Between personal power and collective capacity."

"I'm making the choice I can live with."

"Even if it gets you killed?"

"Especially then."

She almost smiled. "Hobb would hate that answer."

"Hobb would pretend to hate that answer while secretly being proud."

"You're learning."

I was. Slowly. In small increments that the System barely noticed, in ways it didn't have metrics for.

That night I opened two corridors instead of three. Used the saved Thread to reinforce a section of Hobb's distribution network where a surveillance node had been getting too attentive—a gentle nudge that convinced the node its calibration was slightly off, sending its readings into maintenance review limbo for twenty-four hours.

Nobody gained a level. Nobody unlocked a skill. Nobody's Thread counter ticked up in a way that would impress the progression models.

But two hundred families in District Nine ate dinner.

And the Concordance, for all its Arbiters and Variance Offices and governance-layer authority, couldn't figure out how a supply chain was running through their checkpoints like water through fingers—because the supply chain was made of people they'd already decided didn't matter.

**STATUS UPDATE:**
**Location: Veyrun, District 9 (rotating safe houses)**
**Operation: Supply chain maintenance — Day 6**
**Corridors opened: 14 total (2-3 per day, 20-min windows)**
**Supply restoration: ~70% of pre-squeeze allocation**
**Distribution network: 23 active nodes (shopkeepers, services, residential contacts)**
**Broadsheet circulation: ~2,000 copies across 4 districts**
**Level: 15**
**Thread: 14 (recovering slowly)**
**Attention: 26 watchers (slight decrease — low-profile operations reducing signature)**
**Null Anchor: Still destroyed. Still hurts.**
**Growth rate: Below class average. Deliberate choice.**
**Personal note: There's a version of me that would chase the levels. Push the limits. Find the biggest fault, chain the most complex exploit, burn Thread like it's free. That version would be stronger. That version would also be alone, because you can't protect people and maximize power at the same time. The System wants me to choose power. The System can wait.**

---

*End of Chapter 20*
