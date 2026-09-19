<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="p8tarjblc"/><path class="lgaao8o_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:geogebra-geometry" {...props}></Icon>
<style>
:global(.lgaao8o_f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.123 4.348L14.335 29.962h29.576z");
}

:global(.p8tarjblc) {
  cx: 17.069px;
  cy: 30.672px;
  r: 12.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
