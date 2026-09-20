<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bu8ore6lj"/><path class="hwh3wzbtm"/><path class="f6o19s4sp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ironing-board-outline-bold" {...props}></Icon>
<style>
:global(.bu8ore6lj) {
  d: path("M3 6h14a3 3 0 0 1 0 6H3Z");
}

:global(.f6o19s4sp) {
  d: path("M13 12c1 3 2 6 3 8");
}

:global(.hwh3wzbtm) {
  d: path("M7 12c-1 3 -2 6 -3 8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
