<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z7tucwrjl"/><path class="buq3pfbrk"/><path class="muzi7xbvm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bikepacking" {...props}></Icon>
<style>
:global(.buq3pfbrk) {
  d: path("M5.75 16H12l4.5-7.5H9l3 7.5m-6.25 0L9 8.5v-2m-1.5 0h3m6 2l1.75 7.5M16.5 8.5L16 6h2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.muzi7xbvm) {
  d: path("M9 7c-3 0-5.5.5-6.5 2c1.5 1 4 .75 6.5-.25");
}

:global(.z7tucwrjl) {
  d: path("M2.25 16a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m12.5 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
