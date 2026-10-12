<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="g66jxprfo"/><rect class="dzcy4xb8q"/><circle class="e4h9difwy"/><circle class="jibjxvl9d"/><path class="tcev49bgw"/><rect class="o6jzkmknc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:column-greek" {...props}></Icon>
<style>
:global(.dzcy4xb8q) {
  width: 6px;
  height: 12.5px;
  x: 9px;
  y: 5.75px;
  rx: 0.5px;
}

:global(.e4h9difwy) {
  cx: 4.5px;
  cy: 7.25px;
  r: 1.5px;
}

:global(.g66jxprfo) {
  width: 18.5px;
  height: 3px;
  x: 2.75px;
  y: 2.75px;
  rx: 0.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jibjxvl9d) {
  cx: 19.5px;
  cy: 7.25px;
  r: 1.5px;
}

:global(.o6jzkmknc) {
  width: 13px;
  height: 3px;
  x: 5.5px;
  y: 18.25px;
  rx: 0.75px;
}

:global(.tcev49bgw) {
  d: path("M12 8.75v6.5");
}

</style>
