<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jmilqbbwv"/><path class="q1usdm86y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:button-set" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jmilqbbwv) {
  d: path("M4 8.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0");
}

:global(.q1usdm86y) {
  d: path("M12 16.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0M3 19a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M8.5 8.5h.01m2.99 0h.01");
}

</style>
