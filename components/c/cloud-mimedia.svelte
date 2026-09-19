<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="t4b659o-m"/><circle class="v1xj1aczo"/><circle class="fy7gm4ujj"/><circle class="aqljibbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:cloud-mimedia" {...props}></Icon>
<style>
:global(.aqljibbxb) {
  cx: 36.629px;
  cy: 19.377px;
  r: 6.871px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.fy7gm4ujj) {
  cx: 32.394px;
  cy: 27.987px;
  r: 9.494px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.t4b659o-m) {
  cx: 24px;
  cy: 24px;
  r: 15.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.v1xj1aczo) {
  cx: 14.965px;
  cy: 26.55px;
  r: 10.465px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
