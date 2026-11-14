<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gur0pvb_o"/><path class="x949k2mzr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:daylight-lamp" {...props}></Icon>
<style>
:global(.gur0pvb_o) {
  d: path("M3.5 21h8m-4 0l-2.75-8.5L13.5 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x949k2mzr) {
  d: path("M12 9.5a5 5 0 0 1 10 0Zm1.5 2.75l-1.25 2.25m4.75-2v3m3.5-3.25l1.25 2.25");
}

</style>
