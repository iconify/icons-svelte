<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ygzhvrbcl"/><circle class="uayb89x8a"/><circle class="nw5wotbap"/><circle class="n-rw3fbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lio-occitanie" {...props}></Icon>
<style>
:global(.n-rw3fbxt) {
  cx: 5.988px;
  cy: 32.965px;
  r: 1.488px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.nw5wotbap) {
  cx: 18.155px;
  cy: 15.035px;
  r: 1.488px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.uayb89x8a) {
  cx: 33.791px;
  cy: 24.744px;
  r: 9.709px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ygzhvrbcl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.054 14.564v19.889m6.101-14.88v14.582");
}

</style>
