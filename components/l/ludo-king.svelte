<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="gb87zqbby"/><circle class="s4yo5xbpu"/><circle class="fyl-gnt7x"/><circle class="ra5-11bvm"/></g><path class="d_2wopbad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ludo-king" {...props}></Icon>
<style>
:global(.d_2wopbad) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.5 11.738l-3.75 5l-3.75-5l-3.75 5l-3.75-5v10.299h15z");
}

:global(.fyl-gnt7x) {
  cx: 29.375px;
  cy: 30.887px;
  r: 5.375px;
}

:global(.gb87zqbby) {
  cx: 7.875px;
  cy: 30.887px;
  r: 5.375px;
}

:global(.ra5-11bvm) {
  cx: 40.125px;
  cy: 30.887px;
  r: 5.375px;
}

:global(.s4yo5xbpu) {
  cx: 18.625px;
  cy: 30.887px;
  r: 5.375px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
