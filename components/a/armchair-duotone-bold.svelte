<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k-f7ahbzo"/><path class="gam3cw54g"/><path class="aghgwx55f"/><path class="ehvaisl2i"/><path class="xm60vxbgs"/><path class="ys-dg812g"/><path class="q1cfkyb_k"/><path class="hhn28yosy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:armchair-duotone-bold" {...props}></Icon>
<style>
:global(.aghgwx55f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 20v-8h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ehvaisl2i) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 20v-8h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gam3cw54g) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hhn28yosy) {
  d: path("M21 20v-8h-4");
}

:global(.k-f7ahbzo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 16V5h10v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q1cfkyb_k) {
  d: path("M3 20v-8h4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xm60vxbgs) {
  d: path("M7 16V5h10v11");
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

</style>
