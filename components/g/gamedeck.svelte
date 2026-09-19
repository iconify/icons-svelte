<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xtc7zkchr"/><circle class="tcoxa_bpn"/><circle class="hufsp4zsx"/><circle class="ve6bxkbjc"/><circle class="jr74z7bzz"/><path class="xyvqhc1ru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:gamedeck" {...props}></Icon>
<style>
:global(.hufsp4zsx) {
  cx: 39.125px;
  cy: 24px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.jr74z7bzz) {
  cx: 35.25px;
  cy: 27.875px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.tcoxa_bpn) {
  cx: 31.375px;
  cy: 24px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ve6bxkbjc) {
  cx: 35.25px;
  cy: 20.125px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.xtc7zkchr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25 2.543v42.914c11.458-.533 20.48-9.969 20.5-21.439c-.001-11.484-9.028-20.94-20.5-21.475m-2 .035c-11.458.534-20.48 9.969-20.5 21.44c.02 11.47 9.042 20.905 20.5 21.438V24H7.625");
}

:global(.xyvqhc1ru) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.25 29.625v-11.25");
}

</style>
