<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v0dherhqk"/><path class="u2bz_abgl"/><path class="nm2vcvi7u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:floppy-archive" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nm2vcvi7u) {
  d: path("M9.5 5.5V9h6V5.5m-6 16V15h8v6.5");
}

:global(.u2bz_abgl) {
  d: path("M8 5.5h9l4 4v10a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2v-12a2 2 0 0 1 2-2");
}

:global(.v0dherhqk) {
  d: path("M3 17V4.5a2 2 0 0 1 2-2h10");
}

</style>
