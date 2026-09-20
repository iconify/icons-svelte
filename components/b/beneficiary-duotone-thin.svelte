<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z1ra8bb5p"/><path class="hn4kykb4m"/><path class="iz9s08bfh"/><path class="vujkqyb_z"/><path class="a3eibhdgt"/><path class="z26gfvqcs"/><path class="u7m7z6ojw"/><path class="wuk2mlziz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:beneficiary-duotone-thin" {...props}></Icon>
<style>
:global(.a3eibhdgt) {
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
}

:global(.hn4kykb4m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iz9s08bfh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4.5 9.5h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u7m7z6ojw) {
  d: path("M10 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.vujkqyb_z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 19h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wuk2mlziz) {
  d: path("M7 19h10");
}

:global(.z1ra8bb5p) {
  fill: currentColor;
  d: path("M10 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.z26gfvqcs) {
  d: path("M4.5 9.5h15");
}

</style>
