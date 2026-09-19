<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lw36eabip"/><path class="zzpxenbgs"/><circle class="znaicmrtz"/><circle class="qmoxv5bji"/><circle class="nvm3z7gpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:facer" {...props}></Icon>
<style>
:global(.lw36eabip) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.779 12.777h26.054a3.65 3.65 0 0 0 3.648-3.65h0a3.65 3.65 0 0 0-3.649-3.648H9.482a4 4 0 0 0-4 4V38.83a3.65 3.65 0 0 0 3.648 3.65h0a3.65 3.65 0 0 0 3.649-3.649z");
}

:global(.nvm3z7gpf) {
  cx: 19.972px;
  cy: 30.159px;
  r: 0.75px;
  fill: currentColor;
}

:global(.qmoxv5bji) {
  cx: 9.63px;
  cy: 9.583px;
  r: 0.75px;
  fill: currentColor;
}

:global(.znaicmrtz) {
  cx: 19.972px;
  cy: 19.924px;
  r: 0.75px;
  fill: currentColor;
}

:global(.zzpxenbgs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.927 23.573h16.481l3.55-7.297h-20.03a3.65 3.65 0 0 0-3.65 3.648h0a3.65 3.65 0 0 0 3.65 3.65Zm3.648 10.143h8.068l4.035-7.298h-15.4a4 4 0 0 0-4 4V42.48h7.297z");
}

</style>
