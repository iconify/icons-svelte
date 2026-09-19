<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="qtgsqktdi"/><g class="y9tr6bcfx"><circle class="juxor0bjw"/><path class="m9560kbyx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:musicplayer" {...props}></Icon>
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

:global(.juxor0bjw) {
  cx: 21.5px;
  cy: 29.25px;
  r: 3.5px;
}

:global(.m9560kbyx) {
  d: path("M25 29.25v-14m0 0h5v4h-5z");
}

:global(.qtgsqktdi) {
  cx: 24px;
  cy: 24px;
  r: 14.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
