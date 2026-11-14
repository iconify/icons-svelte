<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n793uemyd"/><path class="zg7m4e2-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:golf-gps" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n793uemyd) {
  d: path("M10.375 4.5h3.25A4.375 4.375 0 0 1 18 8.875v8.75A4.375 4.375 0 0 1 13.625 22h-3.25A4.375 4.375 0 0 1 6 17.625v-8.75A4.375 4.375 0 0 1 10.375 4.5M15 2v2.5");
}

:global(.zg7m4e2-s) {
  d: path("M12 16.5C10.5 15 9 13 9 11a3 3 0 0 1 6 0c0 2-1.5 4-3 5.5m0-5.5h.01");
}

</style>
