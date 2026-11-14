<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fhv_rob_i"/><path class="qg_dtcc0b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:file-receipt" {...props}></Icon>
<style>
:global(.fhv_rob_i) {
  d: path("M7 2.5h6.5l6 6v13L17 20.25l-2.5 1.25l-2.5-1.25l-2.5 1.25L7 20.25L4.5 21.5V5A2.5 2.5 0 0 1 7 2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qg_dtcc0b) {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4m-11 3h7m-7 3.5H13");
}

</style>
