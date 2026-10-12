<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="f7r42znre"/><path class="crd9ipobb"/><rect class="wbkoa1e-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mosaic-plot" {...props}></Icon>
<style>
:global(.crd9ipobb) {
  d: path("M9.75 2.75v18.5m-7-7h7m0-6.25h11.5");
}

:global(.f7r42znre) {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wbkoa1e-z) {
  width: 6.5px;
  height: 8.25px;
  x: 12.25px;
  y: 10.5px;
  rx: 1px;
}

</style>
