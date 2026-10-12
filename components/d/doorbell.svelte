<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="um53i40nw"/><path class="klgu-xdto"/><circle class="gmf9qrbcd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:doorbell" {...props}></Icon>
<style>
:global(.gmf9qrbcd) {
  cx: 12px;
  cy: 14.75px;
  r: 2.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.klgu-xdto) {
  d: path("M10.25 7.25h3.5");
}

:global(.um53i40nw) {
  width: 11.5px;
  height: 18.5px;
  x: 6.25px;
  y: 2.75px;
  rx: 5.75px;
}

</style>
