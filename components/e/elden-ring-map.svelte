<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="vnq4b5bqx"/><circle class="ir-lbacxu"/><circle class="wqqxznbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:elden-ring-map" {...props}></Icon>
<style>
:global(.ir-lbacxu) {
  cx: 30.112px;
  cy: 29.645px;
  r: 12.888px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.vnq4b5bqx) {
  cx: 23.439px;
  cy: 18.355px;
  r: 12.888px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.wqqxznbjw) {
  cx: 17.888px;
  cy: 29.645px;
  r: 12.888px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
