<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="xakrkvy8r"/><circle class="smh8hwt4g"/><ellipse class="h1kq2qb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:package-names" {...props}></Icon>
<style>
:global(.h1kq2qb4t) {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 21.5px;
  ry: 14px;
}

:global(.smh8hwt4g) {
  cx: 24px;
  cy: 24px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.xakrkvy8r) {
  cx: 24px;
  cy: 24px;
  r: 10px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
