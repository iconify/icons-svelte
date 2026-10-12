<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="yq-244b_m"/><path class="elpjnkr8g"/><rect class="bnqq1pyph"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:masonry" {...props}></Icon>
<style>
:global(.bnqq1pyph) {
  width: 9.5px;
  height: 6.5px;
  x: 7.25px;
  y: 8.25px;
  rx: 1px;
}

:global(.elpjnkr8g) {
  d: path("M12 14.75v6.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yq-244b_m) {
  width: 18.5px;
  height: 6.5px;
  x: 2.75px;
  y: 14.75px;
  rx: 1px;
}

</style>
