<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bazq81bsf"/><path class="dqsvlfbgk"/><path class="d3xn50bni"/><path class="oy7fa3gbk"/><path class="zvb1nubon"/><path class="wuktrpbtg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:passport-duotone-thin" {...props}></Icon>
<style>
:global(.bazq81bsf) {
  fill: currentColor;
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.d3xn50bni) {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.dqsvlfbgk) {
  fill: currentColor;
  d: path("M11 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oy7fa3gbk) {
  d: path("M8 2v20");
}

:global(.wuktrpbtg) {
  d: path("M11 15h8");
}

:global(.zvb1nubon) {
  d: path("M11 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
