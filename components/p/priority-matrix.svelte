<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yp-jwtbuv"/><path class="x96-ovbwk"/><path class="t4t5nhbet"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:priority-matrix" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t4t5nhbet) {
  d: path("M5.625 14h1.75A2.625 2.625 0 0 1 10 16.625v1.75A2.625 2.625 0 0 1 7.375 21h-1.75A2.625 2.625 0 0 1 3 18.375v-1.75A2.625 2.625 0 0 1 5.625 14m11 0h1.75A2.625 2.625 0 0 1 21 16.625v1.75A2.625 2.625 0 0 1 18.375 21h-1.75A2.625 2.625 0 0 1 14 18.375v-1.75A2.625 2.625 0 0 1 16.625 14");
}

:global(.x96-ovbwk) {
  fill: currentColor;
  d: path("M16.625 3h1.75A2.625 2.625 0 0 1 21 5.625v1.75A2.625 2.625 0 0 1 18.375 10h-1.75A2.625 2.625 0 0 1 14 7.375v-1.75A2.625 2.625 0 0 1 16.625 3");
}

:global(.yp-jwtbuv) {
  d: path("M5.625 3h1.75A2.625 2.625 0 0 1 10 5.625v1.75A2.625 2.625 0 0 1 7.375 10h-1.75A2.625 2.625 0 0 1 3 7.375v-1.75A2.625 2.625 0 0 1 5.625 3");
}

</style>
