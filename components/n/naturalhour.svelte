<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="qkt2_lgop"/><circle class="chj0y-b2g"/><path class="rq6nv4b7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:naturalhour" {...props}></Icon>
<style>
:global(.chj0y-b2g) {
  cx: 23.999px;
  cy: 24px;
  r: 15.991px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
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

:global(.qkt2_lgop) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5v5.508m-14.944.534l3.894 3.895m26.538-3.345l-3.896 3.894");
}

:global(.rq6nv4b7r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 8.008V24m15.993 0H8.008M2.5 24h5.508m31.977 0H45.5M12.958 35.568l-3.895 3.895m26.398-4.319l3.9 3.899m-15.362.949V45.5");
}

</style>
