<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="rmn0_9bsr"/><path class="nqndpsbne"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:earth-globe-space" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nqndpsbne) {
  d: path("M10.5 6.25a3.5 7.25 0 0 0 0 14.5M3.53 11.5q6.97 3.5 13.94 0M19 2.75q.27 1.98 2.25 2.25q-1.98.27-2.25 2.25q-.27-1.98-2.25-2.25q1.98-.27 2.25-2.25");
}

:global(.rmn0_9bsr) {
  cx: 10.5px;
  cy: 13.5px;
  r: 7.25px;
}

</style>
