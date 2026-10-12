<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dw77c535m"/><path class="ln7171bmu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:comb" {...props}></Icon>
<style>
:global(.dw77c535m) {
  width: 18.5px;
  height: 4.5px;
  x: 2.75px;
  y: 5.25px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ln7171bmu) {
  d: path("M5 9.75v8.5m2.5-8.5v9.5m2.5-9.5v9.5m2.5-9.5v9.5m2.5-9.5v9.5m2.5-9.5v9.5m2.5-9.5v8.5");
}

</style>
