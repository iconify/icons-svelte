<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="xjrus5b9w"/><circle class="ipvrskbrp"/><circle class="rj6br6-io"/><circle class="op-2bfn4i"/></g><path class="k_cg59fny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:audi-bkk-service" {...props}></Icon>
<style>
:global(.ipvrskbrp) {
  cx: 19.189px;
  cy: 17.817px;
  r: 6.067px;
}

:global(.k_cg59fny) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.35 32.25a2 2 0 1 1 0 4h-3.3v-8h3.3a2 2 0 1 1 0 4m0 0h-3.3m7.3-4v8m4.3 0l-3.294-4l3.294-3.973m-3.294 3.973H22.35m6.3-4v8m4.3 0l-3.294-4l3.294-3.973m-3.294 3.973H28.65");
}

:global(.op-2bfn4i) {
  cx: 38.433px;
  cy: 17.817px;
  r: 6.067px;
}

:global(.rj6br6-io) {
  cx: 28.811px;
  cy: 17.817px;
  r: 6.067px;
}

:global(.xjrus5b9w) {
  cx: 9.567px;
  cy: 17.817px;
  r: 6.067px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
