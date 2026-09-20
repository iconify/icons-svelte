<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bstg2h-sl"/><path class="ay2m_8giq"/><path class="t_m3g48-w"/><path class="aiuhe2bla"/><path class="p14ufobya"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:author-duotone-thin" {...props}></Icon>
<style>
:global(.aiuhe2bla) {
  d: path("M3.5 15a4.5 4.5 0 0 1 9 0");
}

:global(.ay2m_8giq) {
  fill: currentColor;
  d: path("m13 17 5 -5 2 2 -5 5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.bstg2h-sl) {
  fill: currentColor;
  d: path("M5 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p14ufobya) {
  d: path("m13 17 5 -5 2 2 -5 5Z");
}

:global(.t_m3g48-w) {
  d: path("M5 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
