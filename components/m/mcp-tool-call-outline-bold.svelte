<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="f6ppytj7e"/><path class="uormpdb9p"/><path class="oong2tffv"/><path class="yrwh_6bgk"/><path class="v7ievg3-e"/><path class="u98_rdemn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mcp-tool-call-outline-bold" {...props}></Icon>
<style>
:global(.f6ppytj7e) {
  d: path("M12 10h3a3 3 0 0 1 3 3v3a3 3 0 0 1 -3 3H9a3 3 0 0 1 -3 -3v-3l3 -3Z");
}

:global(.oong2tffv) {
  d: path("M12 5v5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u98_rdemn) {
  d: path("m12.5 13 2 2 -2 2");
}

:global(.uormpdb9p) {
  d: path("M9 5v5");
}

:global(.v7ievg3-e) {
  d: path("M9.5 15h5");
}

:global(.yrwh_6bgk) {
  d: path("M15 5v5");
}

</style>
