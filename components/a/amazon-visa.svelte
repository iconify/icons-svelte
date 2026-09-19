<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><rect class="i-z0ehbqh"/><path class="o9yw82kuc"/></g><circle class="cpk0fnbgt"/><g class="y9tr6bcfx"><path class="cat7z4bfb"/><path class="gar_tub4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:amazon-visa" {...props}></Icon>
<style>
:global(.cat7z4bfb) {
  d: path("M32.28 29.7c1.113-.45 3.092-1.048 3.688-.326c.644.781-.17 2.477-.92 3.794");
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

:global(.gar_tub4z) {
  d: path("M11.798 30.223c1.759 1.397 6.954 3.535 12.488 3.535c5.276 0 8.497-1.912 10.167-3.08");
}

:global(.i-z0ehbqh) {
  width: 24.536px;
  height: 14px;
  x: 11.753px;
  y: 10.668px;
  rx: 2.409px;
  ry: 2.409px;
}

:global(.o9yw82kuc) {
  d: path("M14.003 20.84h3.568m2.684-.02h7.492m-15.914-6.285H36.17");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
