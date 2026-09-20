<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dom865bkj"/><path class="xoaby-lkq"/><path class="qdgfzsc3i"/><path class="daopjcy2e"/><path class="uq8mh8b8n"/><path class="fkin8acuf"/><path class="t-euypbap"/><path class="kpspt_bpo"/><path class="yo-0d--rc"/><path class="jnysnpbhj"/><path class="uto0n9pso"/><path class="fs--blxyx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:key-pair-duotone-regular" {...props}></Icon>
<style>
:global(.daopjcy2e) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 8v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dom865bkj) {
  fill: currentColor;
  d: path("M3 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.fkin8acuf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 13v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fs--blxyx) {
  d: path("M9 13v3");
}

:global(.jnysnpbhj) {
  d: path("M17 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.kpspt_bpo) {
  d: path("M7 8h10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qdgfzsc3i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 8h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t-euypbap) {
  d: path("M3 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.uq8mh8b8n) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 16h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uto0n9pso) {
  d: path("M7 16h10");
}

:global(.xoaby-lkq) {
  fill: currentColor;
  d: path("M17 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yo-0d--rc) {
  d: path("M15 8v3");
}

</style>
