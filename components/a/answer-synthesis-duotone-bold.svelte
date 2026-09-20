<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m_pa0sbgw"/><path class="eb8o-4buj"/><path class="qor244zue"/><path class="g-ki51tst"/><path class="l9zp39bmq"/><path class="sy21-w-qb"/><path class="b7nacdcee"/><path class="d223d_x9q"/><path class="d_scobift"/><path class="ymrjh3b_x"/><path class="k2jd848hu"/><path class="f2m4wubik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:answer-synthesis-duotone-bold" {...props}></Icon>
<style>
:global(.b7nacdcee) {
  d: path("M3 6h6");
}

:global(.d_scobift) {
  d: path("M3 18h6");
}

:global(.d223d_x9q) {
  d: path("M3 12h6");
}

:global(.eb8o-4buj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f2m4wubik) {
  d: path("M13 12h8");
}

:global(.g-ki51tst) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 8 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k2jd848hu) {
  d: path("m9 16 4 -4");
}

:global(.l9zp39bmq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 16 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m_pa0sbgw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qor244zue) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sy21-w-qb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ymrjh3b_x) {
  d: path("m9 8 4 4");
}

</style>
