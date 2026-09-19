<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="f_v_dfbgn"/><path class="aa4bwl42f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:pinout" {...props}></Icon>
<style>
:global(.aa4bwl42f) {
  d: path("M41.304 11.24c-8.7 12.268-19.65 19.83-35.352 24.444m38.637-17.876c-10.321 16.446-21.942 20.09-33.976 23.016");
}

:global(.f_v_dfbgn) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
