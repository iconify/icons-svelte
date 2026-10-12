<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="la1uxcbjt"/><rect class="t0sugtvly"/><path class="wk22e6-7t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lock-reset" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.la1uxcbjt) {
  d: path("M4.52 8.51a8.25 8.25 0 1 1 .08 6.99m-.85-11v4.25H8");
}

:global(.t0sugtvly) {
  width: 6.5px;
  height: 5px;
  x: 8.75px;
  y: 11.25px;
  rx: 1px;
}

:global(.wk22e6-7t) {
  d: path("M10.25 11.25V10a1.75 1.75 0 0 1 3.5 0v1.25");
}

</style>
