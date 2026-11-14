<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gzoc8cc-l"/><path class="w5b35db_y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:camera-pan-tilt" {...props}></Icon>
<style>
:global(.gzoc8cc-l) {
  d: path("M9.375 7.5h5.25a2.625 2.625 0 0 1 2.625 2.625v3.75a2.625 2.625 0 0 1-2.625 2.625h-5.25a2.625 2.625 0 0 1-2.625-2.625v-3.75A2.625 2.625 0 0 1 9.375 7.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w5b35db_y) {
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0M4 9.5L2 12l2 2.5m16-5l2 2.5l-2 2.5M9.5 4.5l2.5-2l2.5 2m-5 15l2.5 2l2.5-2");
}

</style>
