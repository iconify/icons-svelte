<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="zm2js9vrn"/><path class="m5k8xi6tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:pentagram" {...props}></Icon>
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

:global(.m5k8xi6tb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.812 30.691h-9.624l-2.974-9.153L24 15.882l7.786 5.656z");
}

:global(.zm2js9vrn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 45.5l-4.812-14.809H3.617l12.597-9.153l-4.812-14.809L24 15.882l12.597-9.153l-4.811 14.809l12.597 9.153H28.812z");
}

</style>
