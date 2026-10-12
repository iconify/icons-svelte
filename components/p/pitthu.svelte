<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="pdrpd7bza"/><rect class="dhmu2xb9q"/><rect class="eb-t8obue"/><circle class="zgau9oblh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pitthu" {...props}></Icon>
<style>
:global(.dhmu2xb9q) {
  width: 10px;
  height: 3.75px;
  x: 5.25px;
  y: 13.75px;
  rx: 1px;
}

:global(.eb-t8obue) {
  width: 7px;
  height: 3.75px;
  x: 6.75px;
  y: 10px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pdrpd7bza) {
  width: 13px;
  height: 3.75px;
  x: 3.75px;
  y: 17.5px;
  rx: 1px;
}

:global(.zgau9oblh) {
  cx: 18px;
  cy: 6px;
  r: 3.25px;
}

</style>
