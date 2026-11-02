# cheap vps providers: RackNerd's $21.99/Year KVM Plans, Lifetime Renewal Pricing, and How to Pick the Right One

Most people searching for cheap VPS providers want the same three things: a low real monthly cost, no nasty renewal surprise in year two, and enough specs to actually run something. The market splits cleanly here. Unmanaged KVM plans start around $2/month equivalent on annual billing, fully managed plans run $10–$100/month, and the gap between "first-year promo price" and "renewal price" is where most of the disappointment happens.

That second point is why RackNerd keeps coming up in budget-hosting communities. Its current KVM VPS specials start at **$21.99/year** (about $1.83/month), and the official FAQ states these rates are "lifetime recurring" — you renew at the same price for as long as you keep the service. There's no promo-price cliff. This article walks through every plan currently on the site, what the renewal math looks like over three years, the fine print that most roundup articles skip, and which plan fits which workload.

> **Quick picks**
> - Most people: the **2 GB KVM special** — 2 vCPU, 35 GB SSD, 5 TB transfer, **$35.99/year**, officially flagged as the most popular plan. 👉 [Grab the 2 GB plan at $35.99/year](https://my.racknerd.com/aff.php?aff=11397&pid=953)
> - Tightest budget: the 1 GB special at $21.99/year.
> - Databases, Docker stacks, or AI tools: the 6 GB or 8 GB specials.
> - Want to test before committing a year? RackNerd also sells monthly KVM plans from $17.99/month — and note the specials themselves are non-refundable, so monthly is the low-risk entry.

## What "cheap" actually means in the VPS market right now

Cheap unmanaged VPS pricing starts at roughly $2.00/month on the lowest tiers, with managed plans ranging from $10 to $100/month depending on the provider. That's the baseline you're shopping against, and it's worth knowing what a few more dollars per month buys at the bigger names.

Take Hostinger's KVM 1 plan, independently benchmarked in May 2026: 1 vCPU, 4 GB RAM, 50 GB NVMe, 4 TB of transfer. Billed monthly it's $19.49. The advertised entry price — around $6.99/month — requires committing to a year upfront, and the renewal rate climbs to $12.99/month. So the true first-year cost is about $84, and year two jumps to roughly $156. Independent performance testing graded that plan's raw CPU power and network performance at the bottom of its scale, though the same review notes that low grades on budget VPS plans don't always mean poor real-world value — price-weighted comparisons matter.

This is the pattern worth understanding before comparing providers: headline prices in this market are usually first-term promotional rates tied to long prepayments, and the renewal rate is the number that actually determines your long-term cost. RackNerd competes from the opposite direction — lower headline pricing to begin with ($21.99/year works out to about $1.83/month), annual prepay, and a renewal rate that stays exactly where it started. User feedback on the big-name providers echoes the distinction; among the recurring complaints in Trustpilot reviews of Hostinger's VPS line are renewal prices far above the intro rate and undisclosed CPU throttling. Neither complaint applies to RackNerd's model, though it has its own trade-offs — covered below.

## RackNerd's full list of VPS specials (annual billing)

The specials page currently shows five KVM VPS plans, all billed yearly. Every plan includes full root access, one dedicated IPv4 address, a 1Gbps port, KVM virtualization with the ctrl control panel, and instant activation after payment — you can deploy in multiple datacenter locations.

| Plan | CPU / RAM | Storage | Monthly transfer | Price | Order |
| --- | --- | --- | --- | --- | --- |
| 1 GB KVM VPS | 1 vCPU / 1 GB | 20 GB SSD | 3 TB | $21.99/yr | [ Order the 1 GB plan](https://my.racknerd.com/aff.php?aff=11397&pid=952) |
| 2 GB KVM VPS (most popular) | 2 vCPU / 2 GB | 35 GB SSD | 5 TB | $35.99/yr | [ Order the 2 GB plan](https://my.racknerd.com/aff.php?aff=11397&pid=953) |
| 4 GB KVM VPS | 3 vCPU / 4 GB | 60 GB SSD | 7 TB | $59.99/yr | [ Order the 4 GB plan](https://my.racknerd.com/aff.php?aff=11397&pid=954) |
| 6 GB KVM VPS | 6 vCPU / 6 GB | 100 GB SSD | 12 TB | $89.99/yr | [ Order the 6 GB plan](https://my.racknerd.com/aff.php?aff=11397&pid=955) |
| 8 GB KVM VPS | 7 vCPU / 8 GB | 150 GB SSD | 20 TB | $119.99/yr | [ Order the 8 GB plan](https://my.racknerd.com/aff.php?aff=11397&pid=956) |

Two things worth noticing in that table. First, the jump from 4 GB to 6 GB is where the CPU count doubles (3 to 6 vCPU) — if your workload is CPU-bound rather than RAM-bound, that's the tier to look at. Second, storage is modest across the line; these plans are priced for compute and bandwidth, not for hoarding files.

Older articles still floating around quote a $10.60/year or $11.29/year entry plan from past Black Friday and New Year promotions. Those are gone — the current floor is $21.99/year. If you see "$11 RackNerd VPS" somewhere, check the date before trusting the rest of that article.

## The standard KVM VPS line (monthly billing, plus a 512 MB annual option)

Besides the specials, RackNerd runs a standard KVM VPS line, with the Los Angeles page (Asia-optimized network) currently listing seven plans:

| Plan | CPU / RAM | Storage (RAID-10) | Transfer | Price | Order |
| --- | --- | --- | --- | --- | --- |
| 512 MB | 1 vCore / 512 MB | 30 GB SSD | 500 GB | $26.99/yr | [ Order the 512 MB plan](https://my.racknerd.com/aff.php?aff=11397&pid=1) |
| 1 GB | 2 vCore / 1 GB | 50 GB SSD | 1 TB | $17.99/mo | [ Try the 1 GB monthly plan](https://my.racknerd.com/aff.php?aff=11397&pid=20) |
| 2 GB | 3 vCore / 2 GB | 75 GB SSD | 2 TB | $20.59/mo | [ Order the 2 GB monthly plan](https://my.racknerd.com/aff.php?aff=11397&pid=21) |
| 4 GB | 4 vCore / 4 GB | 130 GB SSD | 3 TB | $24.59/mo | [ Order the 4 GB monthly plan](https://my.racknerd.com/aff.php?aff=11397&pid=22) |
| 6 GB | 5 vCore / 6 GB | 170 GB SSD | 4 TB | $27.59/mo | [ Order the 6 GB monthly plan](https://my.racknerd.com/aff.php?aff=11397&pid=23) |
| 8 GB | 6 vCore / 8 GB | 220 GB SSD | 5 TB | $36.59/mo | [ Order the 8 GB monthly plan](https://my.racknerd.com/aff.php?aff=11397&pid=24) |
| 12 GB | 7 vCore / 12 GB | 300 GB SSD | 6 TB | $55.99/mo | [ Order the 12 GB monthly plan](https://my.racknerd.com/aff.php?aff=11397&pid=25) |

The standard line gives you more storage and more cores per gigabyte of RAM than the specials — the 2 GB standard plan has 3 vCores and 75 GB versus the special's 2 vCores and 35 GB. The catch is price: at $20.59/month, the standard 2 GB plan costs roughly seven times more per year than the $35.99 special. Community reviews of RackNerd's lineup reach the same conclusion — the standard plans make sense for short-term projects or when you need to cancel anytime; for anything you plan to keep, the specials win on cost by a wide margin.

## Renewal pricing: the real three-year cost

RackNerd's specials renew at the purchase price, permanently. The official specials FAQ puts it plainly: "These RackNerd VPS specials are lifetime recurring. You can renew at the same rate for as long as you decide to keep the service."

The math over three years for the 1 GB special: $21.99 × 3 = **$65.97**, or about $1.83/month for the whole period. Contrast that with the promo-then-jump pattern at larger providers — a Hostinger-class plan costs roughly $84 in year one and $156 in year two. The difference compounds fast, and it's the single biggest structural gap between RackNerd and the mainstream cheap-VPS names.

The renewal flow supports the promise: an invoice is generated automatically 14 days before expiry at the original rate, and you can also generate one manually from the client area (Services → your VPS → Generate Renewal Invoice) if you want to pay several years ahead. Long-term users who have renewed multiple times report the invoice amount staying identical. Nothing auto-charges by default — renewal is manual, with an optional auto-recharge toggle in the client area if you'd rather not think about it.

If that flat-renewal guarantee is what settles it for you, 👉 [lock in the 1 GB special at $21.99/year](https://my.racknerd.com/aff.php?aff=11397&pid=952) while the current pricing holds.

## The fine print most cheap VPS roundups skip

Five limitations live in the FAQ and terms rather than on the pricing tables, and each one affects real decisions:

**There is no refund guarantee.** RackNerd's refund policy is case-by-case, with no standard money-back window, no trial period, and no prorated refunds on the annual specials. Account balance prepayments are explicitly non-refundable. If you dispute a payment through your bank and the service was flagged for abuse, an administrative fee of $125–$250 can apply. This is the trade-off behind the low prepaid pricing — which is why testing with a monthly standard plan first is the sensible path if you're unsure.

**Immediate cancellation wipes your data within 24 hours.** Canceling and refund are two different things: an immediate cancellation terminates the VPS within a day and clears all data, with no money back. If you cancel by mistake, open a ticket immediately — past the 24-hour mark the data can't be recovered.

**Cancel-before-renewal needs notice.** To stop a service from renewing, you submit a cancellation notice through the client area at least 5 days before the renewal date. Miss it and a new invoice lands in your account; since nothing auto-charges, the worst case is an unpaid invoice you ignore.

**Unpaid services terminate after about a week — and then data is gone.** The grace period works like this: miss the invoice and the server gets suspended with data retained while reminders arrive; most services auto-terminate around 7 days past due, and after termination data is permanently deleted. Users who've paid a few days into the grace window report everything coming back intact, but don't count on more than that. Set up off-site automated backups from day one.

**Upgrading out of a special resets your pricing.** You can upgrade to a higher plan by paying the difference, but moving from an annual special to a standard plan means your renewal price follows the standard pricing from then on. The locked-in rate only survives if you stay on the special line. Plan your tier before ordering rather than assuming you'll upgrade later.

Two more things belong in this section rather than a marketing table. First, it's unmanaged: you get root access and 24/7 ticket support, but RackNerd doesn't administer your server, and that's precisely why the price sits roughly an order of magnitude below DigitalOcean or Vultr for similar specs, per long-form community reviews. If you need migrations, monitoring, and an SLA, budget for the managed tier elsewhere. Second, routing is ordinary international bandwidth optimized with Noction IRP — not a premium direct route. Community guides for mainland-China users recommend the west coast locations (Los Angeles DC03, Los Angeles DC02 on 2 GB and above, San Jose, Seattle — latency typically just over 150ms) while cautioning that evening-peak throughput can fluctuate. If you need CN2 GIA-class lines, this isn't it.

On promo codes: the specials are already the discounted price and generally can't be stacked with codes. Discount codes claiming 30% off VPS plans are mostly stale leftovers from old promotions; the recurring codes that verifiably still work apply to dedicated servers, not VPS. You don't need a code to get the prices in the tables above.

## Who should buy something else

RackNerd is the wrong tool in three situations. You need managed hosting — migrations, monitoring, and someone to call when the disk fills up — in which case the managed tiers at larger providers charge more per month for exactly that layer. You're running compliance-sensitive or revenue-critical production where no-refund terms and unmanaged support aren't acceptable risk. Or your workload needs guaranteed CPU performance: Hostinger's KVM line, for all its renewal-price jump, publishes benchmarked per-vCPU throughput, and other cheap providers like OVHcloud and IONOS list 4 GB RAM plans in the €4–5/month range that fit different regions and billing preferences. None of those fit the "lowest total cost over years" goal as well as RackNerd's specials, but they're legitimate choices depending on what you're optimizing for.

For everything else — personal projects, blogs, small sites, proxies, monitoring scripts, DNS, Docker playgrounds, self-hosted AI tooling — the specials are hard to beat on total cost. The ctrl panel includes one-click installs for Ollama, AnythingLLM, LibreChat, n8n, and Coolify; mind the RAM minimums though. n8n and Coolify run comfortably from 2 GB, most AI apps want 4 GB, and OpenClaw wants 8 GB.

## How to buy: steps, payment, and one registration tip

The whole process takes a few minutes:

1. Pick a plan from the specials table and choose your datacenter location and OS (CentOS, Rocky Linux, AlmaLinux, Debian, Ubuntu, or a custom ISO via ticket).
2. Register with a real email — server credentials go there.
3. Pay. Options include Alipay (scan or login, handy for mainland users), PayPal, major credit cards, cryptocurrency, and bank wire.
4. Activation is instant after payment; the email contains your IP and root password. SSH in and you're done.

One tip that saves a support round-trip: register from your usual network IP. Orders placed through proxies or VPNs can trigger a fraud check and manual review, which delays activation by a day or two.

Two extras worth knowing: Los Angeles and France locations provide up to 100 free IPv6 addresses on request — just open a ticket after ordering — and upgrading between plans takes about a minute of downtime, essentially a reboot. If you want to check latency before paying, RackNerd's datacenter pages offer looking-glass tools and test download files for each location, which beats guessing.

## FAQ

**Do RackNerd's cheap VPS specials renew at the same price?**
Yes. The official FAQ states the specials are lifetime recurring — you renew at your original rate indefinitely. Invoices generate 14 days before expiry, and renewal is manual unless you enable auto-recharge.

**Is there a refund if I change my mind?**
Not as a guarantee. Refunds are handled case-by-case with no standard money-back window, and the annual specials are effectively non-refundable. That's why testing with a monthly standard plan ($17.99/month and up) is the safer path if you're on the fence — and remember that immediate cancellation deletes your data within 24 hours, so back up first.

**How many datacenters does RackNerd have?**
Twenty locations across North America, Europe, and Asia, including Los Angeles, San Jose, Seattle, Dallas, Chicago, New York, Ashburn, Toronto, London, Amsterdam, and Dublin. Specials can be deployed in multiple locations; mainland-China-facing projects tend to favor the LA and west coast nodes.

**Can I self-host or run AI tools on these plans?**
Yes — every special is a full KVM VPS with root access, and the ctrl panel ships one-click installers for Ollama, AnythingLLM, LibreChat, n8n, Coolify, and others. Anything past 2 GB of RAM gets you into AI-app territory; OpenClaw needs the 8 GB tier.

## Picking your plan before you order

If you just need a cheap, reliable box for a blog, a few scripts, or a personal VPN: the 1 GB special at $21.99/year does the job, and the 2 GB at $35.99/year is the safer margin for roughly double the price. Running Docker containers or a small production site: start at the 4 GB or 6 GB special. Self-hosting AI tools: 8 GB, no exceptions for OpenClaw. And if your project might not survive twelve months, take the monthly standard plan instead — the flexibility is worth the higher rate, and you can always move to a special later at whatever the current pricing is.

One last check before paying: confirm the datacenter location matches where your users (or you) actually are — run a ping or MTR through the looking glass first, because transfers are generous but routing is ordinary international bandwidth. And since cancellation after termination means permanent data loss, get an off-site backup routine running on day one. If the location checks out, 👉 [check RackNerd's current specials and pick your tier](https://bit.ly/RacKnerd) — the renewal rate you lock in now is the rate you'll keep for as long as you run the server, which is the whole point of buying annual in the first place.
