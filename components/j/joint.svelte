<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p-ubj1bmc"/><path class="yl9hdvbpc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:joint" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p-ubj1bmc) {
  d: path("M10.25 2.5v5.25m3.5-5.25v5.25M9 10.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

:global(.yl9hdvbpc) {
  d: path("M17.479 10.729a5.5 5.5 0 0 1-10.958 0M10 15.5v6m4-6v6");
}

</style>
