<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hbdbg_bcy"/><path class="lyjarcbwz"/><path class="fkopq9pyc"/><path class="go1co5b_o"/><path class="mxb6569jn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chat-more-outline-bold" {...props}></Icon>
<style>
:global(.fkopq9pyc) {
  d: path("M7 10.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.go1co5b_o) {
  d: path("M11 10.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hbdbg_bcy) {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.lyjarcbwz) {
  d: path("M7 18v3l3 -3");
}

:global(.mxb6569jn) {
  d: path("M15 10.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
