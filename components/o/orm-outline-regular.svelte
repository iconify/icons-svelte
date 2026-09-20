<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pquf1ccxc"/><path class="kzt32ybrc"/><path class="g6jjwho2g"/><path class="qv4k8z3yq"/><path class="t2kj97bba"/><path class="y0y0ccsoe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:orm-outline-regular" {...props}></Icon>
<style>
:global(.g6jjwho2g) {
  d: path("M4 13h4");
}

:global(.kzt32ybrc) {
  d: path("M5 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pquf1ccxc) {
  d: path("M2 7a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.qv4k8z3yq) {
  d: path("M14 7a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

:global(.t2kj97bba) {
  d: path("M15 10h6");
}

:global(.y0y0ccsoe) {
  d: path("M10 12h4");
}

</style>
