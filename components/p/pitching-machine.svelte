<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ib28slb6t"/><path class="sqtll3b5m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pitching-machine" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ib28slb6t) {
  d: path("M3 9a5.25 5.25 0 1 0 10.5 0A5.25 5.25 0 1 0 3 9m5.25 5.25L4 21.5m4.25-7.25l4.25 7.25");
}

:global(.sqtll3b5m) {
  d: path("M6.25 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10.25-.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
