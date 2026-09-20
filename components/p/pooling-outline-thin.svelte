<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tfto2zbdp"/><path class="xlz01ub4s"/><path class="ml5vh8o3m"/><path class="n_1n94xtx"/><path class="godgg2x3f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pooling-outline-thin" {...props}></Icon>
<style>
:global(.godgg2x3f) {
  d: path("M8 16.5a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ml5vh8o3m) {
  d: path("M17 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.n_1n94xtx) {
  d: path("M9.5 8.5 12 11l2.5 -2.5");
}

:global(.tfto2zbdp) {
  d: path("M5 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.xlz01ub4s) {
  d: path("M11 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
