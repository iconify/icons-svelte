<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="e-uqlbb7e"/><circle class="ut1xs1bjo"/><path class="xkuen-bkc"/></g><g class="y9tr6bcfx"><circle class="hnl9ncatj"/><path class="s2joaaccx"/><circle class="bnfcmiboh"/><path class="qpdeej54g"/><circle class="unyea3xra"/><path class="t3uftrh9n"/><circle class="vrycm_1xn"/><path class="pym1nhb9c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:playerpro" {...props}></Icon>
<style>
:global(.bnfcmiboh) {
  cx: 7.635px;
  cy: 40.365px;
  r: 2.135px;
}

:global(.e-uqlbb7e) {
  cx: 24px;
  cy: 24px;
  r: 18.5px;
}

:global(.hnl9ncatj) {
  cx: 7.635px;
  cy: 7.635px;
  r: 2.135px;
}

:global(.pym1nhb9c) {
  d: path("m38.826 38.887l3.018 3.017");
}

:global(.qpdeej54g) {
  d: path("m9.174 38.887l-3.018 3.017");
}

:global(.s2joaaccx) {
  d: path("M9.113 9.174L6.096 6.156");
}

:global(.t3uftrh9n) {
  d: path("m38.887 9.174l3.017-3.018");
}

:global(.unyea3xra) {
  cx: 40.365px;
  cy: 7.635px;
  r: 2.135px;
}

:global(.ut1xs1bjo) {
  cx: 24px;
  cy: 24px;
  r: 14.705px;
}

:global(.vrycm_1xn) {
  cx: 40.365px;
  cy: 40.365px;
  r: 2.135px;
}

:global(.xkuen-bkc) {
  d: path("M30.494 24L21.3 29.308V18.692z");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
