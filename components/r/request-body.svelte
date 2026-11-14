<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ktvep6pgg"/><path class="tufj21bif"/><path class="rp4oqibyb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:request-body" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ktvep6pgg) {
  d: path("M4 10v9a2.5 2.5 0 0 0 2.5 2.5h11A2.5 2.5 0 0 0 20 19v-9");
}

:global(.rp4oqibyb) {
  d: path("M10.25 10.25L13 13l2.75-2.75M8.5 17.5h8");
}

:global(.tufj21bif) {
  d: path("M3 4.5h6a4 4 0 0 1 4 4V13");
}

</style>
