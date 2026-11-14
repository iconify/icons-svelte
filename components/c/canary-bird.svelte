<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k1l2azbhv"/><path class="k6u1d7seg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:canary-bird" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k1l2azbhv) {
  d: path("M4 18.5C4 14 8 11 12.5 11c4 0 5.5 2 5.5 4.5c0 3-3 4.5-6 4.5s-6-.5-8-1.5m8.5-11a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

:global(.k6u1d7seg) {
  d: path("M19.75 6.75za.875.875 0 0 1 0 1.5a.825.825 0 0 1-1.25-.708v-.084a.825.825 0 0 1 1.25-.708M9 20v1.75M13 20v1.75M16.25 7h.01");
}

</style>
