<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="oe8a5va_l"/><path class="luiokdbcj"/><circle class="d4da7x21x"/><path class="jdgyzzbqi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:permit" {...props}></Icon>
<style>
:global(.d4da7x21x) {
  cx: 16.75px;
  cy: 16.75px;
  r: 4.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jdgyzzbqi) {
  d: path("m14.75 16.75l1.5 1.5l2.75-3");
}

:global(.luiokdbcj) {
  d: path("M7.5 9.75v-2.5l2.5-2l2.5 2v2.5Zm0 3.25H14m-6.5 3h3");
}

:global(.oe8a5va_l) {
  width: 13.5px;
  height: 18.5px;
  x: 4.25px;
  y: 2.75px;
  rx: 1.5px;
}

</style>
