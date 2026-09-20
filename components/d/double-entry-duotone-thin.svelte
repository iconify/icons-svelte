<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ck7sgubpk"/><path class="znhw8kbaa"/><path class="c8aozj6tk"/><path class="u8fmtulhw"/><path class="k6nj2fbya"/><path class="bg2ejdbaq"/><path class="b1ja9gnou"/><path class="z0kumyy5w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:double-entry-duotone-thin" {...props}></Icon>
<style>
:global(.b1ja9gnou) {
  d: path("M5 10h4.5");
}

:global(.bg2ejdbaq) {
  d: path("M12 5v16");
}

:global(.c8aozj6tk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 10h4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ck7sgubpk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.u8fmtulhw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14.5 14H19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z0kumyy5w) {
  d: path("M14.5 14H19");
}

:global(.znhw8kbaa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 5v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
