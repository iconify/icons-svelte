<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l1d7gebxl"/><rect class="bm23k1bps"/><rect class="u2djl85ai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:card-shuffle" {...props}></Icon>
<style>
:global(.bm23k1bps) {
  width: 7.5px;
  height: 11.25px;
  x: 3px;
  y: 10px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l1d7gebxl) {
  d: path("M6.75 6.75q5.25-5 10.5 0m0-2.5v2.5h-2.5m-8-2.5v2.5h2.5");
}

:global(.u2djl85ai) {
  width: 7.5px;
  height: 11.25px;
  x: 13.5px;
  y: 10px;
  rx: 1.5px;
}

</style>
