<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g_qdjbcak"/><path class="w118l0p0e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:golf-hook" {...props}></Icon>
<style>
:global(.g_qdjbcak) {
  d: path("M9 18.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3.5-5.75C14.5 9.5 16 5.5 8 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w118l0p0e) {
  d: path("M10 3L7.5 5L10 7");
}

</style>
