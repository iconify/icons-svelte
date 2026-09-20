<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ltbxi_2yl"/><path class="l7q8onb4q"/><path class="gykfelgpq"/><path class="jt7d488ke"/><path class="zdawi4qef"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:logit-lens-outline-thin" {...props}></Icon>
<style>
:global(.gykfelgpq) {
  d: path("M13 11v7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jt7d488ke) {
  d: path("M13 7a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.l7q8onb4q) {
  d: path("M9 9v9");
}

:global(.ltbxi_2yl) {
  d: path("M5 13v5");
}

:global(.zdawi4qef) {
  d: path("m20 10 2 2");
}

</style>
