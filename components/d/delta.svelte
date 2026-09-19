<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="jf7a7tbyo"/><circle class="pi7qwvbtq"/><circle class="mmvx2aclv"/><circle class="vxr-sx9cm"/><circle class="s1eqzzbkl"/><circle class="h9xomwwcb"/><circle class="x97150bfl"/><circle class="ayscgq6zu"/><circle class="zgq-0acry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:delta" {...props}></Icon>
<style>
:global(.ayscgq6zu) {
  cx: 9.13px;
  cy: 24.459px;
  r: 3.631px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.h9xomwwcb) {
  cx: 24px;
  cy: 39.329px;
  r: 3.631px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.jf7a7tbyo) {
  cx: 24px;
  cy: 24.459px;
  r: 3.631px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.mmvx2aclv) {
  cx: 16.565px;
  cy: 17.025px;
  r: 3.631px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.pi7qwvbtq) {
  cx: 31.435px;
  cy: 31.894px;
  r: 3.631px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.s1eqzzbkl) {
  cx: 31.435px;
  cy: 17.025px;
  r: 3.631px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.vxr-sx9cm) {
  cx: 16.565px;
  cy: 31.894px;
  r: 3.631px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.x97150bfl) {
  cx: 38.87px;
  cy: 24.459px;
  r: 3.631px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zgq-0acry) {
  cx: 24px;
  cy: 9.59px;
  r: 3.631px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
