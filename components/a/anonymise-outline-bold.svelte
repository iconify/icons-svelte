<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ufzn_r3vk"/><path class="avdamgajo"/><path class="jds7y1b0v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:anonymise-outline-bold" {...props}></Icon>
<style>
:global(.avdamgajo) {
  d: path("M6 21a6 6 0 0 1 12 0");
}

:global(.jds7y1b0v) {
  d: path("M7 8a1.5 1.5 0 0 1 1.5 -1.5h7A1.5 1.5 0 0 1 17 8a1.5 1.5 0 0 1 -1.5 1.5h-7A1.5 1.5 0 0 1 7 8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ufzn_r3vk) {
  d: path("M9 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
