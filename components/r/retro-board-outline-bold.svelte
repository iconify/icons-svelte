<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jrpnc2pnl"/><path class="mihda9d9w"/><path class="g-g6w6buq"/><path class="me7c_bbry"/><path class="uv-0dacjj"/><path class="mf-afdped"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:retro-board-outline-bold" {...props}></Icon>
<style>
:global(.g-g6w6buq) {
  d: path("M7 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.jrpnc2pnl) {
  d: path("M15 5h3a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
}

:global(.me7c_bbry) {
  d: path("M15 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.mf-afdped) {
  d: path("M15 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.mihda9d9w) {
  d: path("M12 9v8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uv-0dacjj) {
  d: path("M7 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
