<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aqyofsnqg"/><path class="kf5i1zqrr"/><path class="a04fpgbvk"/><path class="p97-zvx-p"/><path class="qzwh4exzn"/><path class="t7sxv2y7b"/><path class="quv6fgbpo"/><path class="w6zsztb2w"/><path class="oumlmtbql"/><path class="h9o82-b1h"/><path class="oio7uh0en"/><path class="j4_olc1js"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mutual-duotone-regular" {...props}></Icon>
<style>
:global(.a04fpgbvk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.aqyofsnqg) {
  fill: currentColor;
  d: path("M4 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.h9o82-b1h) {
  d: path("M15 16a3 3 0 0 1 6 0");
}

:global(.j4_olc1js) {
  d: path("M10 14h4");
}

:global(.kf5i1zqrr) {
  fill: currentColor;
  d: path("M16 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oio7uh0en) {
  d: path("M10 11h4");
}

:global(.oumlmtbql) {
  d: path("M16 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.p97-zvx-p) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 16a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.quv6fgbpo) {
  d: path("M4 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.qzwh4exzn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t7sxv2y7b) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 14h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w6zsztb2w) {
  d: path("M3 16a3 3 0 0 1 6 0");
}

</style>
