<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aqyofsnqg"/><path class="kf5i1zqrr"/><path class="gtii7k5jz"/><path class="lvlbl1p9r"/><path class="kmfi7db8w"/><path class="k3wnukrax"/><path class="quv6fgbpo"/><path class="w6zsztb2w"/><path class="oumlmtbql"/><path class="h9o82-b1h"/><path class="oio7uh0en"/><path class="j4_olc1js"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mutual-duotone-thin" {...props}></Icon>
<style>
:global(.aqyofsnqg) {
  fill: currentColor;
  d: path("M4 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gtii7k5jz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h9o82-b1h) {
  d: path("M15 16a3 3 0 0 1 6 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j4_olc1js) {
  d: path("M10 14h4");
}

:global(.k3wnukrax) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 14h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kf5i1zqrr) {
  fill: currentColor;
  d: path("M16 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.kmfi7db8w) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lvlbl1p9r) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 16a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oio7uh0en) {
  d: path("M10 11h4");
}

:global(.oumlmtbql) {
  d: path("M16 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.quv6fgbpo) {
  d: path("M4 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.w6zsztb2w) {
  d: path("M3 16a3 3 0 0 1 6 0");
}

</style>
