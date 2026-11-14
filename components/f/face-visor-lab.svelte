<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wpcn3sith"/><path class="xtiqw_bbf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:face-visor-lab" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wpcn3sith) {
  d: path("M7 7.5c0-3.25 2.25-5 5-5s5 1.75 5 5");
}

:global(.xtiqw_bbf) {
  d: path("M7 7.5q5-1.25 10 0a2 2 0 0 1 0 4q-5-1.25-10 0a2 2 0 0 1 0-4m0 4c0 3.25 2.25 5.25 5 5.25s5-2 5-5.25m-13 10q8-3.5 16 0");
}

</style>
