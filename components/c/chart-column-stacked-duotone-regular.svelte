<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pd-i35blz"/><path class="iulb4mb6k"/><path class="zv6r23bea"/><path class="yr6jlbc6d"/><path class="szm2jsciq"/><path class="daopjcy2e"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="e71sokbbi"/><path class="sb7rl7wyu"/><path class="pt73j1ikv"/><path class="yo-0d--rc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chart-column-stacked-duotone-regular" {...props}></Icon>
<style>
:global(.daopjcy2e) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 8v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e71sokbbi) {
  d: path("M9 12v8");
}

:global(.iulb4mb6k) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.pd-i35blz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pt73j1ikv) {
  d: path("M15 14v6");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.sb7rl7wyu) {
  d: path("M9 6v3");
}

:global(.szm2jsciq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yo-0d--rc) {
  d: path("M15 8v3");
}

:global(.yr6jlbc6d) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 6v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zv6r23bea) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
