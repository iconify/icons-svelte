<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w9wi7_b7i"/><path class="wgl-673uv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:egg" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w9wi7_b7i) {
  d: path("M14.5 2.75c4.25 1.25 5 8.25 3.75 13C17 20 13.5 22.25 9.5 21.25c-3.75-1-6-4.75-4.75-9.25C6 7.25 10 1.75 14.5 2.75");
}

:global(.wgl-673uv) {
  d: path("M8 14.5c0-2 .75-4 2-5.5");
}

</style>
