<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b48wk2z1d"/><circle class="xjp-epbsz"/><circle class="dn21gubvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:airmini" {...props}></Icon>
<style>
:global(.b48wk2z1d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.477 36.767l-10.8-29.016l-.02.008c-.489-1.311-1.502-2.418-2.916-2.944a4.99 4.99 0 0 0-6.418 2.936l-10.8 29.016a4.991 4.991 0 0 0 9.355 3.482L24 23.8l6.123 16.45a4.993 4.993 0 0 0 6.418 2.937a4.99 4.99 0 0 0 2.937-6.419Z");
}

:global(.dn21gubvj) {
  cx: 34.801px;
  cy: 38.509px;
  r: 4.991px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.xjp-epbsz) {
  cx: 13.198px;
  cy: 38.509px;
  r: 4.991px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
