<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r4h1y5b9l"/><g class="y9tr6bcfx"><path class="hiv-k1b5z"/><circle class="g67k4dbcl"/><circle class="c3lbm7m4q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:file-code-2" {...props}></Icon>
<style>
:global(.c3lbm7m4q) {
  cx: 24px;
  cy: 34.022px;
  r: 2.12px;
}

:global(.g67k4dbcl) {
  cx: 24px;
  cy: 24.978px;
  r: 2.12px;
}

:global(.hiv-k1b5z) {
  d: path("M18.818 20.857a2.725 2.725 0 0 0-2.725 2.725v3.193A2.725 2.725 0 0 1 13.37 29.5a2.725 2.725 0 0 1 2.724 2.725v3.193a2.725 2.725 0 0 0 2.725 2.725m10.363 0a2.725 2.725 0 0 0 2.725-2.725v-3.193A2.725 2.725 0 0 1 34.63 29.5a2.725 2.725 0 0 1-2.724-2.725v-3.193a2.725 2.725 0 0 0-2.725-2.725");
}

:global(.r4h1y5b9l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 15.5h-9a2 2 0 0 1-2-2v-9h-18a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h27a2 2 0 0 0 2-2zm-11-11l11 11");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
