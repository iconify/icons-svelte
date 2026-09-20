<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="siqrysbwb"/><path class="wdz8jebrc"/><path class="okcmurbzx"/><path class="pquf1ccxc"/><path class="kzt32ybrc"/><path class="g6jjwho2g"/><path class="qv4k8z3yq"/><path class="t2kj97bba"/><path class="y0y0ccsoe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:orm-duotone-bold" {...props}></Icon>
<style>
:global(.g6jjwho2g) {
  d: path("M4 13h4");
}

:global(.kzt32ybrc) {
  d: path("M5 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.okcmurbzx) {
  fill: currentColor;
  d: path("M14 7a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.pquf1ccxc) {
  d: path("M2 7a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.qv4k8z3yq) {
  d: path("M14 7a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.siqrysbwb) {
  fill: currentColor;
  d: path("M2 7a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.t2kj97bba) {
  d: path("M15 10h6");
}

:global(.wdz8jebrc) {
  fill: currentColor;
  d: path("M5 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.y0y0ccsoe) {
  d: path("M10 12h4");
}

</style>
