<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ck7sgubpk"/><path class="c58ve3zov"/><path class="w5kgvzb8e"/><path class="n3cxssblb"/><path class="k6nj2fbya"/><path class="x50q_4bdr"/><path class="u1mon9cdo"/><path class="o_qgmvj5j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:change-capture-duotone-thin" {...props}></Icon>
<style>
:global(.c58ve3zov) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 10h18");
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

:global(.n3cxssblb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m20 13 -3 3h2.5l-3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o_qgmvj5j) {
  d: path("m20 13 -3 3h2.5l-3 3");
}

:global(.u1mon9cdo) {
  d: path("M3 15h9");
}

:global(.w5kgvzb8e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 15h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x50q_4bdr) {
  d: path("M3 10h18");
}

</style>
