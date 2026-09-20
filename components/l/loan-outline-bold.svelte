<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ky4omnbla"/><path class="l0v-b4kbr"/><path class="az5esj3_g"/><path class="d_yxl29go"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:loan-outline-bold" {...props}></Icon>
<style>
:global(.az5esj3_g) {
  d: path("M10.5 9.5 8 12l2.5 2.5");
}

:global(.d_yxl29go) {
  d: path("M13.5 9.5 16 12l-2.5 2.5");
}

:global(.ky4omnbla) {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

:global(.l0v-b4kbr) {
  d: path("M8 12h8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
