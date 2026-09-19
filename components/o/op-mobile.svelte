<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nu0qfgbko"/><circle class="bsxq1jlyv"/><circle class="qr08x1bhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:op-mobile" {...props}></Icon>
<style>
:global(.bsxq1jlyv) {
  cx: 32.5px;
  cy: 24px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.nu0qfgbko) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5v-39");
}

:global(.qr08x1bhu) {
  cx: 15.5px;
  cy: 24px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
