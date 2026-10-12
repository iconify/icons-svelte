<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="y6nr_abgb"/><path class="vdxf26b1d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:battery" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vdxf26b1d) {
  d: path("M21.25 10.5v3M6 10v4m3.25-4v4m3.25-4v4m3.25-4v4");
}

:global(.y6nr_abgb) {
  width: 16px;
  height: 10.5px;
  x: 2.75px;
  y: 6.75px;
  rx: 2.5px;
}

</style>
