<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mtuecs9vi"/><path class="tpq6uz-ms"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:exam-admit-card" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mtuecs9vi) {
  d: path("M6 5h12a3.5 3.5 0 0 1 3.5 3.5v7A3.5 3.5 0 0 1 18 19H6a3.5 3.5 0 0 1-3.5-3.5v-7A3.5 3.5 0 0 1 6 5");
}

:global(.tpq6uz-ms) {
  d: path("M7 8.5h2a1.5 1.5 0 0 1 1.5 1.5v3.5A1.5 1.5 0 0 1 9 15H7a1.5 1.5 0 0 1-1.5-1.5V10A1.5 1.5 0 0 1 7 8.5m6.5.5h5m-5 3h5m-5 3h3");
}

</style>
