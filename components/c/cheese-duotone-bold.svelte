<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="skovrp7bf"/><path class="t7edyg0pd"/><path class="i9yv2ebba"/><path class="hxfvjbc9o"/><path class="qot4e3zhe"/><path class="vzyxlnb8e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cheese-duotone-bold" {...props}></Icon>
<style>
:global(.hxfvjbc9o) {
  d: path("M4 19v-6l6 -6h10v12Z");
}

:global(.i9yv2ebba) {
  fill: currentColor;
  d: path("M14 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qot4e3zhe) {
  d: path("M8 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.skovrp7bf) {
  fill: currentColor;
  d: path("M4 19v-6l6 -6h10v12Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.t7edyg0pd) {
  fill: currentColor;
  d: path("M8 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vzyxlnb8e) {
  d: path("M14 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
