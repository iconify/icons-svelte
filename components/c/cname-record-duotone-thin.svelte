<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ck7sgubpk"/><path class="fx63l30wc"/><path class="bt_2bvgpa"/><path class="tdsnubcpt"/><path class="rs3fs1bee"/><path class="k6nj2fbya"/><path class="ae-e09b3w"/><path class="rkhcgsbdl"/><path class="zbpm1d36f"/><path class="hrjweb57d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cname-record-duotone-thin" {...props}></Icon>
<style>
:global(.ae-e09b3w) {
  d: path("M3 12h18");
}

:global(.bt_2bvgpa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ck7sgubpk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fx63l30wc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hrjweb57d) {
  d: path("m9 15 3 -3 3 3");
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.rs3fs1bee) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 15 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tdsnubcpt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 8 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zbpm1d36f) {
  d: path("m9 8 3 -3 3 3");
}

</style>
