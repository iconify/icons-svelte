<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vhnbtvbtn"/><path class="jyd5g773m"/><path class="d_scobift"/><path class="u-x8-1cug"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:relevance-score-outline-thin" {...props}></Icon>
<style>
:global(.d_scobift) {
  d: path("M3 18h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jyd5g773m) {
  d: path("M3 13h12");
}

:global(.u-x8-1cug) {
  d: path("M17 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

</style>
