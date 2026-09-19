<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="io5tdnd-j"/><circle class="bo4x37bwj"/><circle class="u-kpwsbrz"/><circle class="erscrub_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ajman-bank-connect" {...props}></Icon>
<style>
:global(.bo4x37bwj) {
  cx: 31.5px;
  cy: 24px;
  r: 14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.erscrub_v) {
  cx: 24px;
  cy: 31.5px;
  r: 14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.io5tdnd-j) {
  cx: 16.5px;
  cy: 24px;
  r: 14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.u-kpwsbrz) {
  cx: 24px;
  cy: 16.5px;
  r: 14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
