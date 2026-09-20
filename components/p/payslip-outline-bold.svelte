<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ky4omnbla"/><path class="zwh7a2bjz"/><path class="gnhsdzb8d"/><path class="elmoo_bpw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:payslip-outline-bold" {...props}></Icon>
<style>
:global(.elmoo_bpw) {
  d: path("M15 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.gnhsdzb8d) {
  d: path("M6 13h6");
}

:global(.ky4omnbla) {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.zwh7a2bjz) {
  d: path("M6 9h9");
}

</style>
