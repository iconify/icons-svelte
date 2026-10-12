<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gq28ubc8p"/><rect class="qy_nz69uh"/><rect class="qiccohb_j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:headset-dj" {...props}></Icon>
<style>
:global(.gq28ubc8p) {
  d: path("M4.5 13.25V12a7.5 7.5 0 0 1 15 0v1.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qiccohb_j) {
  width: 6.75px;
  height: 4.5px;
  x: 14.5px;
  y: 13.25px;
  rx: 2px;
}

:global(.qy_nz69uh) {
  width: 4.5px;
  height: 8px;
  x: 2.75px;
  y: 12.75px;
  rx: 2px;
}

</style>
