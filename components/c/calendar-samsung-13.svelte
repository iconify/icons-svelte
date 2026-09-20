<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="qgxd-lmrb"/><path class="mnpd36bmd"/></g><path class="kzykk8swa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:calendar-samsung-13" {...props}></Icon>
<style>
:global(.kzykk8swa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-4v1a3.5 3.5 0 1 1-7 0v-1h-8v1a3.5 3.5 0 1 1-7 0v-1h-3a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

:global(.mnpd36bmd) {
  d: path("M24.405 21.336c1.107-.922 2.3-1.343 4.979-1.336l.622.004a4 4 0 1 1 0 7.998m-3.074 0h3.074");
}

:global(.qgxd-lmrb) {
  d: path("m14.28 22.2l4-2.2m0 0v16m6.127-1.35c1.104.926 2.297 1.35 4.975 1.35h.624a4 4 0 1 0 0-7.998");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
