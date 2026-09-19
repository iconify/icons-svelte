<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="bn9n4ubgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:delhi-metro-navigator" {...props}></Icon>
<style>
:global(.bn9n4ubgs) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M3.506 30.5h40.988m-40.988-13h40.988M17.5 30.5l13-13");
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

</style>
