<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g7go0l5ag"/><path class="wew0vnk_n"/><path class="j6riv-b4h"/><path class="w0e70wbbt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:leaderboard-internal-outline-bold" {...props}></Icon>
<style>
:global(.g7go0l5ag) {
  d: path("M5 11v8");
}

:global(.j6riv-b4h) {
  d: path("M19 14v5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w0e70wbbt) {
  d: path("M3 21.5h18");
}

:global(.wew0vnk_n) {
  d: path("M12 5v14");
}

</style>
