<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z5q9g_bbk"/><rect class="mwmlm1y3o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:rock-on" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mwmlm1y3o) {
  width: 6.5px;
  height: 2.5px;
  x: 9.25px;
  y: 14.25px;
  rx: 1.25px;
}

:global(.z5q9g_bbk) {
  d: path("M8.25 3zQ9.5 3 9.5 4.25v7q0 .75.75.75H14q.75 0 .75-.75v-5.5q0-1.25 1.25-1.25t1.25 1.25V18.5q0 2.5-2.5 2.5H9.5Q7 21 7 18.5V4.25Q7 3 8.25 3");
}

</style>
