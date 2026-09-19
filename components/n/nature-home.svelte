<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="nmntmgbnp"/><circle class="q332r2vjg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nature-home" {...props}></Icon>
<style>
:global(.nmntmgbnp) {
  d: path("M4.5 28.317h39z");
}

:global(.q332r2vjg) {
  cx: 24px;
  cy: 24px;
  r: 11.1px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
