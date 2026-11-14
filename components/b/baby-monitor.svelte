<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="htwzp261d"/><path class="l8dpkcc8o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:baby-monitor" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.htwzp261d) {
  d: path("M6.5 6H9a3.5 3.5 0 0 1 3.5 3.5v8A3.5 3.5 0 0 1 9 21H6.5A3.5 3.5 0 0 1 3 17.5v-8A3.5 3.5 0 0 1 6.5 6m1 0V2.75");
}

:global(.l8dpkcc8o) {
  d: path("M5.75 13.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10.25-3a4.5 4.5 0 0 1 0 6M19 8a8 8 0 0 1 0 11");
}

</style>
