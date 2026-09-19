<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="oolsii1em"/><path class="hph01vbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lifebox" {...props}></Icon>
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

:global(.hph01vbsi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.16 30.79l11.878 6.86V24.021l-11.878-6.86zm11.879 6.86l11.801-6.811V17.21l-11.802 6.811zM12.16 30.79v11.155m.04-24.805l-9.66 5.576M23.962 10.35l-9.629-5.56m21.511 12.42V6.055m-.041 24.805l9.661-5.576M24.039 37.65l9.628 5.56");
}

:global(.oolsii1em) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.16 17.161l11.878 6.86L35.84 17.21l-11.879-6.86z");
}

</style>
