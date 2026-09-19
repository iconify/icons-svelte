<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="vc6gc3mgm"/><path class="rftf-kbbz"/></g><g class="y9tr6bcfx"><circle class="bybjau59l"/><circle class="se87bac5g"/><rect class="brxpxfbzn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:calendar-9" {...props}></Icon>
<style>
:global(.brxpxfbzn) {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  rx: 4px;
  ry: 4px;
}

:global(.bybjau59l) {
  cx: 32.5px;
  cy: 11px;
  r: 2.5px;
}

:global(.rftf-kbbz) {
  d: path("M19.26 34.025C20.05 35.21 21.431 36 23.604 36H24a5.31 5.31 0 0 0 5.333-5.333v-5.334");
}

:global(.se87bac5g) {
  cx: 15.5px;
  cy: 11px;
  r: 2.5px;
}

:global(.vc6gc3mgm) {
  cx: 24px;
  cy: 25.333px;
  r: 5.333px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
