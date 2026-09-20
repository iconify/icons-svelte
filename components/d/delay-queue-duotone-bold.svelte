<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gwjllcbqv"/><path class="m3bn7sb5q"/><path class="w-icpcn9a"/><path class="xocy_1fwz"/><path class="fmr2g_bno"/><path class="aff9hemvj"/><path class="mz4c5lb-h"/><path class="osjmvib6z"/><path class="le2s8qb-r"/><path class="ffja1hbnj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:delay-queue-duotone-bold" {...props}></Icon>
<style>
:global(.aff9hemvj) {
  d: path("M9 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ffja1hbnj) {
  d: path("M12 16h3.5");
}

:global(.fmr2g_bno) {
  d: path("M3 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.gwjllcbqv) {
  fill: currentColor;
  d: path("M3 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.le2s8qb-r) {
  d: path("M12 13.5V16");
}

:global(.m3bn7sb5q) {
  fill: currentColor;
  d: path("M9 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mz4c5lb-h) {
  d: path("M15 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.osjmvib6z) {
  d: path("M7 16a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w-icpcn9a) {
  fill: currentColor;
  d: path("M15 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xocy_1fwz) {
  fill: currentColor;
  d: path("M7 16a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
