<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n81xq1jkm"/><circle class="gvj9aybtb"/><path class="dlfdxnfxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:chubbyclick" {...props}></Icon>
<style>
:global(.dlfdxnfxy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.64 32.02V9.39h5.86");
}

:global(.gvj9aybtb) {
  cx: 31.05px;
  cy: 32.02px;
  r: 6.59px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.n81xq1jkm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.45 9.39H4.5m0 16.04h16.15M4.5 17.41h24.95");
}

</style>
