<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mxstnobvd"/><circle class="szups_37t"/><circle class="tlf41qc1o"/><path class="vvfvik0qh"/><rect class="a7r3gub2f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lever-pulley" {...props}></Icon>
<style>
:global(.a7r3gub2f) {
  width: 5px;
  height: 5.25px;
  x: 5.75px;
  y: 16px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mxstnobvd) {
  d: path("M7 2.75h10m-5 0v3.5");
}

:global(.szups_37t) {
  cx: 12px;
  cy: 10px;
  r: 3.75px;
}

:global(.tlf41qc1o) {
  cx: 12px;
  cy: 10px;
  r: 1px;
}

:global(.vvfvik0qh) {
  d: path("M8.25 10v6m7.5-6v11.25");
}

</style>
