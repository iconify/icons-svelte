<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gal-xobkx"/><path class="b_qq7dbsh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:impact-volunteer-hours" {...props}></Icon>
<style>
:global(.b_qq7dbsh) {
  d: path("M11.5 3v3L5 18v3m13 0v-6m-2.5 2.5L18 15l2.5 2.5");
}

:global(.gal-xobkx) {
  d: path("M3 3h10.5M3 21h10.5M5 3v3l6.5 12v3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
