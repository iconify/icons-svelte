<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="xuyjp0bnb"/><path class="kqef4tbqv"/><path class="tcl_u7zhf"/><path class="ttxdcjbnj"/><path class="xnnknu4ij"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:humanoid-robot-sharp" {...props}></Icon>
<style>
:global(.kqef4tbqv) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3.25h.01");
}

:global(.tcl_u7zhf) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12.5V16m18.5-3.5V16");
}

:global(.ttxdcjbnj) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 12.75h.01m5.49 0h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.xnnknu4ij) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 16.5h4.5");
}

:global(.xuyjp0bnb) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 7.75h13.5v12.5H5.25zm6.75 0V4");
}

</style>
