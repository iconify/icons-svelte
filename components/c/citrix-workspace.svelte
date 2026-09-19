<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s042v_9ks"/><path class="pby_reb2q"/><circle class="vqogbbbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:citrix-workspace" {...props}></Icon>
<style>
:global(.pby_reb2q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.75 24A10.75 10.75 0 1 1 24 13.25");
}

:global(.s042v_9ks) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24A21.5 21.5 0 1 1 24 2.5");
}

:global(.vqogbbbht) {
  cx: 24px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

</style>
