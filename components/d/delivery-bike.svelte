<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="rslc-9wef"/><circle class="j-97t6czk"/><path class="js1p_vbby"/><rect class="b56bpgb9m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:delivery-bike" {...props}></Icon>
<style>
:global(.b56bpgb9m) {
  width: 3.5px;
  height: 3.25px;
  x: 17.75px;
  y: 4.5px;
  rx: 0.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j-97t6czk) {
  cx: 18px;
  cy: 18px;
  r: 3.25px;
}

:global(.js1p_vbby) {
  d: path("m6 18l3.5-7h5.75m-3.5 7L9.5 11m2.25 7l3.5-7M18 18L14.25 7.25h-2M8 8.75h3");
}

:global(.rslc-9wef) {
  cx: 6px;
  cy: 18px;
  r: 3.25px;
}

</style>
