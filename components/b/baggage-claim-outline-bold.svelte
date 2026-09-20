<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="konffhqhd"/><path class="rjb_q9q1l"/><path class="pmuiqo95v"/><path class="oqfv9rb9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:baggage-claim-outline-bold" {...props}></Icon>
<style>
:global(.konffhqhd) {
  d: path("M6 6.5a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2V12a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

:global(.oqfv9rb9x) {
  d: path("M2 21h20");
}

:global(.pmuiqo95v) {
  d: path("M2 17h20");
}

:global(.rjb_q9q1l) {
  d: path("M10 4.5V2h4v2.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
