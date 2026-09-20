<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="z92okmbgh"/><path class="q8cj1m5wa"/><path class="jrpnc2pnl"/><path class="j1rehpbmf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dashboard-panel-duotone-bold" {...props}></Icon>
<style>
:global(.j1rehpbmf) {
  d: path("M7 12a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v2.5a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

:global(.jrpnc2pnl) {
  d: path("M15 5h3a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
}

:global(.q8cj1m5wa) {
  fill: currentColor;
  d: path("M7 12a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v2.5a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.z92okmbgh) {
  fill: currentColor;
  d: path("M15 5h3a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
