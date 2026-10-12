<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="bkvs37v4d"/><rect class="tjczw_npf"/><rect class="zmyq7-bqa"/><path class="g3bxqq7ow"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:radiator" {...props}></Icon>
<style>
:global(.bkvs37v4d) {
  width: 3px;
  height: 15.75px;
  x: 3.75px;
  y: 3.75px;
  rx: 1.5px;
}

:global(.g3bxqq7ow) {
  d: path("M6.75 7h2.5m3 0h2.5m-8 9h2.5m3 0h2.5m3 0h2.5m0-1.75v3.5m-15 1.75v1.75m11-1.75v1.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tjczw_npf) {
  width: 3px;
  height: 15.75px;
  x: 9.25px;
  y: 3.75px;
  rx: 1.5px;
}

:global(.zmyq7-bqa) {
  width: 3px;
  height: 15.75px;
  x: 14.75px;
  y: 3.75px;
  rx: 1.5px;
}

</style>
