<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i1xxpnvzs"/><path class="kbzrjrl8g"/><path class="kap-jqbyq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:envelope-print" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i1xxpnvzs) {
  d: path("M7 16H5a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-2M7 8V3h10v5");
}

:global(.kap-jqbyq) {
  d: path("m7 12.5l5 3.5l5-3.5");
}

:global(.kbzrjrl8g) {
  d: path("M8.75 12h6.5A1.75 1.75 0 0 1 17 13.75v6a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 7 19.75v-6A1.75 1.75 0 0 1 8.75 12");
}

</style>
