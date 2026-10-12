<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="k6zax5bzt"/><path class="iuzn7bc2u"/><rect class="fo13j9b6c"/><path class="hlrtwo8vd"/><rect class="enjwwwbgv"/><path class="l-v-dxbdz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:candlestick" {...props}></Icon>
<style>
:global(.enjwwwbgv) {
  width: 3.5px;
  height: 7.5px;
  x: 16.75px;
  y: 10.25px;
  rx: 1px;
}

:global(.fo13j9b6c) {
  width: 3.5px;
  height: 7px;
  x: 10.25px;
  y: 5.25px;
  rx: 1px;
}

:global(.hlrtwo8vd) {
  d: path("M12 2.75v2.5m0 7v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iuzn7bc2u) {
  d: path("M5.5 4.25v3.5m0 8.5v3.5");
}

:global(.k6zax5bzt) {
  width: 3.5px;
  height: 8.5px;
  x: 3.75px;
  y: 7.75px;
  rx: 1px;
}

:global(.l-v-dxbdz) {
  d: path("M18.5 6.75v3.5m0 7.5v3.5");
}

</style>
