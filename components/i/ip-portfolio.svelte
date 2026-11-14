<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o3vip2vhj"/><path class="sywkcncgs"/><path class="hj46on3bd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ip-portfolio" {...props}></Icon>
<style>
:global(.hj46on3bd) {
  d: path("M13.237 12.013a1.75 1.75 0 1 1-2.474 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o3vip2vhj) {
  d: path("M2.5 5A1.5 1.5 0 0 1 4 3.5h5L11 6h9a1.5 1.5 0 0 1 1.5 1.5V19a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 19Z");
}

:global(.sywkcncgs) {
  d: path("M8.25 13.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

</style>
