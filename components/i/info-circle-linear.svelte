<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="shu3xdl9q"/><path class="ianaz7b0e"/><path class="db-k4n35p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:info-circle-linear" {...props}></Icon>
<style>
:global(.db-k4n35p) {
  stroke-linejoin: round;
  d: path("M12 8H12.0001");
}

:global(.ianaz7b0e) {
  d: path("M12 17V11");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.shu3xdl9q) {
  cx: 12px;
  cy: 12px;
  r: 10px;
}

</style>
