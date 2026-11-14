<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ed2ek-bth"/><path class="yev75xqlb"/><path class="k4-_0owka"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:flat-washer" {...props}></Icon>
<style>
:global(.ed2ek-bth) {
  d: path("M3 10.5a9 5.5 0 1 0 18 0a9 5.5 0 1 0-18 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k4-_0owka) {
  d: path("M8.5 10.5a3.5 2 0 1 0 7 0a3.5 2 0 1 0-7 0");
}

:global(.yev75xqlb) {
  d: path("M3 10.5V13a9 5.5 0 0 0 18 0v-2.5");
}

</style>
