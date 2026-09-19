<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><g class="y9tr6bcfx"><path class="igfzun03r"/><rect class="d8cmf6beh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:letter-uppercase-circle-q" {...props}></Icon>
<style>
:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.d8cmf6beh) {
  width: 10.6px;
  height: 16px;
  x: 18.7px;
  y: 16px;
  rx: 5.3px;
  ry: 5.3px;
}

:global(.igfzun03r) {
  d: path("M29.3 32L24 26.763");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
