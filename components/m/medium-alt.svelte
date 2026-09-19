<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="y9wlq-ata"/><ellipse class="h5d3tzpwt"/><ellipse class="r1-yc_buy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:medium-alt" {...props}></Icon>
<style>
:global(.h5d3tzpwt) {
  cx: 32.318px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.934px;
  ry: 10.479px;
}

:global(.r1-yc_buy) {
  cx: 42.339px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.161px;
  ry: 10.479px;
}

:global(.y9wlq-ata) {
  cx: 13.979px;
  cy: 24px;
  r: 10.479px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
