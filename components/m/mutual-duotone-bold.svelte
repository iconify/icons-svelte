<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aqyofsnqg"/><path class="kf5i1zqrr"/><path class="g_nzeqb9o"/><path class="s7e-1vb0f"/><path class="r-6mxobrl"/><path class="mki5lh7ms"/><path class="quv6fgbpo"/><path class="w6zsztb2w"/><path class="oumlmtbql"/><path class="h9o82-b1h"/><path class="oio7uh0en"/><path class="j4_olc1js"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mutual-duotone-bold" {...props}></Icon>
<style>
:global(.aqyofsnqg) {
  fill: currentColor;
  d: path("M4 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.g_nzeqb9o) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
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

:global(.mki5lh7ms) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 14h4");
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

:global(.r-6mxobrl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s7e-1vb0f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 16a3 3 0 0 1 6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w6zsztb2w) {
  d: path("M3 16a3 3 0 0 1 6 0");
}

</style>
