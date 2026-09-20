<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h7vr07ufd"/><path class="utlpmrn-a"/><path class="zx-f6ebvw"/><path class="s_wu0ubug"/><path class="k6nj2fbya"/><path class="x50q_4bdr"/><path class="u1mon9cdo"/><path class="o_qgmvj5j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:change-capture-duotone-bold" {...props}></Icon>
<style>
:global(.h7vr07ufd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.o_qgmvj5j) {
  d: path("m20 13 -3 3h2.5l-3 3");
}

:global(.s_wu0ubug) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m20 13 -3 3h2.5l-3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u1mon9cdo) {
  d: path("M3 15h9");
}

:global(.utlpmrn-a) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 10h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x50q_4bdr) {
  d: path("M3 10h18");
}

:global(.zx-f6ebvw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 15h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
