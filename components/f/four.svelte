<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="eivix5byy"/><circle class="zabv6dbsu"/><circle class="faob581ix"/><circle class="be3dg4bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:four" {...props}></Icon>
<style>
:global(.be3dg4bpi) {
  cx: 26.5px;
  cy: 35px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.eivix5byy) {
  cx: 26.5px;
  cy: 24px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.faob581ix) {
  cx: 26.5px;
  cy: 13px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zabv6dbsu) {
  cx: 16px;
  cy: 24px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
