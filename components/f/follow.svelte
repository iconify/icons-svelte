<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="pp8a5cbnn"/><circle class="z6vsygbpw"/><circle class="gxslg9bzd"/><circle class="xb1p4bctw"/><circle class="t_heqb_5d"/><circle class="n8lyiyb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:follow" {...props}></Icon>
<style>
:global(.gxslg9bzd) {
  cx: 14.851px;
  cy: 23.848px;
  r: 3.644px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.n8lyiyb3k) {
  cx: 40.735px;
  cy: 40.275px;
  r: 2.225px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.pp8a5cbnn) {
  cx: 24px;
  cy: 38.551px;
  r: 3.644px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.t_heqb_5d) {
  cx: 7.265px;
  cy: 40.275px;
  r: 2.225px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.xb1p4bctw) {
  cx: 33.149px;
  cy: 23.848px;
  r: 3.644px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.z6vsygbpw) {
  cx: 24px;
  cy: 9.144px;
  r: 3.644px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
