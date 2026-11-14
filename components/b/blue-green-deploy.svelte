<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dfsbc0bat"/><path class="y274tsd-w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:blue-green-deploy" {...props}></Icon>
<style>
:global(.dfsbc0bat) {
  fill: currentColor;
  d: path("M5 5za2.5 2.5 0 0 1 2.5 2.5v9A2.5 2.5 0 0 1 5 19a2.5 2.5 0 0 1-2.5-2.5v-9A2.5 2.5 0 0 1 5 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y274tsd-w) {
  d: path("M19 5za2.5 2.5 0 0 1 2.5 2.5v9A2.5 2.5 0 0 1 19 19a2.5 2.5 0 0 1-2.5-2.5v-9A2.5 2.5 0 0 1 19 5m-8.75 4h3.5m-1.5-1.5l1.5 1.5l-1.5 1.5m1.5 4.5h-3.5m1.5-1.5l-1.5 1.5l1.5 1.5");
}

</style>
