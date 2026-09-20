<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="f_v_dfbgn"/><path class="fkkhc5bem"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ebtedge" {...props}></Icon>
<style>
:global(.f_v_dfbgn) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
}

:global(.fkkhc5bem) {
  d: path("M24.334 24h6.831m3.647 10.561H24.334V13.439h10.478M21.027 31.896a5.23 5.23 0 0 1-4.552 2.665c-2.894 0-5.24-2.364-5.24-5.28v-3.433c0-2.916 2.346-5.28 5.24-5.28c2.893 0 5.239 2.364 5.239 5.28v1.716H11.235");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
