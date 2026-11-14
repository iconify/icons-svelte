<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wtw1his_e"/><path class="ioae2cebf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hearing-range" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ioae2cebf) {
  d: path("M5.25 9a2.25 2.25 0 0 1 4.5 0m5.75-.5a4.5 4.5 0 0 1 0 7m3-10a9 9 0 0 1 0 13");
}

:global(.wtw1his_e) {
  d: path("M2.5 9a5 5 0 0 1 10 0c0 3.5-3.5 4-3.5 7.5a2.5 2.5 0 0 1-5 .5");
}

</style>
