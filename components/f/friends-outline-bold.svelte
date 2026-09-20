<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wc595gblk"/><path class="fozhwebbv"/><path class="bo88vlbuz"/><path class="yak33lb9w"/><path class="bos0j4biy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:friends-outline-bold" {...props}></Icon>
<style>
:global(.bo88vlbuz) {
  d: path("M16 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.bos0j4biy) {
  d: path("M3 21h18");
}

:global(.fozhwebbv) {
  d: path("M10 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wc595gblk) {
  d: path("M4 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.yak33lb9w) {
  d: path("M3 19a9 9 0 0 1 18 0");
}

</style>
