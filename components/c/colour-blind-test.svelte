<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cfyoj_jqw"/><path class="rnac67cfx"/><path class="g_3i87pkq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:colour-blind-test" {...props}></Icon>
<style>
:global(.cfyoj_jqw) {
  d: path("M2.5 10C5 5.5 14 5.5 17 10c-3 4.5-12 4.5-14.5 0");
}

:global(.g_3i87pkq) {
  fill: currentColor;
  d: path("M18 14.25a3.75 3.75 0 0 0 0 7.5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rnac67cfx) {
  d: path("M7.5 10a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m6.75 8a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

</style>
