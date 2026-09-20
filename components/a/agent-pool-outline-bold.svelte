<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xyeuuzvcq"/><path class="gsa3wh0sx"/><path class="quu8uycwi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-pool-outline-bold" {...props}></Icon>
<style>
:global(.gsa3wh0sx) {
  d: path("M17.77 4.78a3 3 0 1 1 -2.54 0");
}

:global(.quu8uycwi) {
  d: path("M3 14v5h18v-5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xyeuuzvcq) {
  d: path("M8.77 4.78a3 3 0 1 1 -2.54 0");
}

</style>
