<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="i52ir2wah"/><circle class="rmzc42dyi"/><circle class="lzy657qln"/><circle class="ifw5dhb7f"/><circle class="j7wxopbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:glider" {...props}></Icon>
<style>
:global(.i52ir2wah) {
  cx: 24px;
  cy: 10.065px;
  r: 4.565px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ifw5dhb7f) {
  cx: 24px;
  cy: 37.935px;
  r: 4.565px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.j7wxopbvk) {
  cx: 10.065px;
  cy: 37.935px;
  r: 4.565px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.lzy657qln) {
  cx: 37.935px;
  cy: 37.935px;
  r: 4.565px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.rmzc42dyi) {
  cx: 37.876px;
  cy: 24px;
  r: 4.565px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
