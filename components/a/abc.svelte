<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><g class="y9tr6bcfx"><circle class="kzaxxjc8o"/><circle class="gbye05btj"/><path class="rl4wifl5e"/></g><path class="gfcrq_3sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:abc" {...props}></Icon>
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

:global(.gbye05btj) {
  cx: 24px;
  cy: 24px;
  r: 4.5px;
}

:global(.gfcrq_3sa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.206 24v4.5M19.5 24v-9");
}

:global(.kzaxxjc8o) {
  cx: 12.706px;
  cy: 24px;
  r: 4.5px;
}

:global(.rl4wifl5e) {
  d: path("M39.325 26.002a4.5 4.5 0 1 1 0-4.003");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
