<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iizzxacfc"/><path class="cycis-bjn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mask-privacy" {...props}></Icon>
<style>
:global(.cycis-bjn) {
  d: path("M5.25 11a2.25 1.5 0 1 0 4.5 0a2.25 1.5 0 1 0-4.5 0m9 0a2.25 1.5 0 1 0 4.5 0a2.25 1.5 0 1 0-4.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iizzxacfc) {
  d: path("M2.5 9c0-1.5 1-2.5 2.5-2.5h14c1.5 0 2.5 1 2.5 2.5v2c0 3.5-2.5 5.5-5.5 5.5c-2 0-3-1.5-4-2.5c-1 1-2 2.5-4 2.5c-3 0-5.5-2-5.5-5.5Z");
}

</style>
