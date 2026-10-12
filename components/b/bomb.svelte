<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="og1g0-edb"/><path class="l5igckbqb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bomb" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l5igckbqb) {
  d: path("M6.75 13.25a3.75 3.75 0 0 1 3-3m5.88-1.38c.75-.75 1.1-1.75.9-2.75M19 2.75q.18 1.32 1.5 1.5q-1.32.18-1.5 1.5q-.18-1.32-1.5-1.5q1.32-.18 1.5-1.5");
}

:global(.og1g0-edb) {
  cx: 10.5px;
  cy: 14px;
  r: 7.25px;
}

</style>
