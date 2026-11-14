<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x-wlrib_o"/><path class="ahtvirbkt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:face-disappointed" {...props}></Icon>
<style>
:global(.ahtvirbkt) {
  d: path("M8.5 17q3.5-2.5 7 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x-wlrib_o) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0M7 9.25l2.75-1.5M17 9.25l-2.75-1.5M8.5 12h.01m6.99 0h.01");
}

</style>
