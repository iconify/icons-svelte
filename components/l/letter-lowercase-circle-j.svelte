<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="cdb83q58c"/><circle class="w-6ipp0zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:letter-lowercase-circle-j" {...props}></Icon>
<style>
:global(.cdb83q58c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.007 18.275v12c0 2.21-1.774 4-3.962 4h0a3.93 3.93 0 0 1-2.802-1.172");
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

:global(.w-6ipp0zu) {
  cx: 27.007px;
  cy: 14.475px;
  r: 0.75px;
  fill: currentColor;
}

</style>
