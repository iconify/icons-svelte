<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><circle class="i7wdi9_uf"/><path class="bxaynub9l"/><circle class="ax-ivwmbs"/><circle class="r8nzeqbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:hyperfocal-pro" {...props}></Icon>
<style>
:global(.ax-ivwmbs) {
  cx: 26.445px;
  cy: 17.802px;
  r: 2.019px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.bxaynub9l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 20h7.184M5.5 28h7.184m22.632-8H42.5m-7.184 8H42.5");
}

:global(.i7wdi9_uf) {
  cx: 24px;
  cy: 24px;
  r: 12px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.i9clfwm2k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

:global(.r8nzeqbne) {
  cx: 24.427px;
  cy: 22.503px;
  r: 1.237px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
