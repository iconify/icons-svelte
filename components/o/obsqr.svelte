<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="sir2o5bpx"/><g class="y9tr6bcfx"><path class="lhn8-l1tz"/><path class="snwnzwb0f"/><circle class="y4qe_oahm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:obsqr" {...props}></Icon>
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

:global(.lhn8-l1tz) {
  d: path("M14.45 14.45h19.1v19.1h-19.1z");
}

:global(.sir2o5bpx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.7 24h42.6m-33.8 8.9v3.6h3.6m17.8 0h3.6v-3.6M15.1 11.5h-3.6v3.6m25 0v-3.6h-3.6");
}

:global(.snwnzwb0f) {
  d: path("M17.8 17.8h12.4v12.4H17.8z");
}

:global(.y4qe_oahm) {
  cx: 24px;
  cy: 24px;
  r: 2.6px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
