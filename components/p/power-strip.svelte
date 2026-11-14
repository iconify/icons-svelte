<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s_qz2wt_f"/><path class="gwwii1b6l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:power-strip" {...props}></Icon>
<style>
:global(.gwwii1b6l) {
  d: path("M5.5 8.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-3.5 4v3c0 4 5 2.5 5 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s_qz2wt_f) {
  d: path("M6 4.5h12A3.5 3.5 0 0 1 21.5 8v1a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 9V8A3.5 3.5 0 0 1 6 4.5");
}

</style>
