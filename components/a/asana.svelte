<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="kuxwdpzmt"/><ellipse class="bq8gd4bzj"/><ellipse class="e846qoojt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:asana" {...props}></Icon>
<style>
:global(.bq8gd4bzj) {
  cx: 34.7px;
  cy: 33.42px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.8px;
  ry: 7.71px;
}

:global(.e846qoojt) {
  cx: 24px;
  cy: 14.58px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.8px;
  ry: 7.71px;
}

:global(.kuxwdpzmt) {
  cx: 13.3px;
  cy: 33.42px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.8px;
  ry: 7.71px;
}

</style>
