<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dqwni1b6f"/><path class="g55pkgb9q"/><path class="z5rak8b7e"/><path class="w9o11dbmt"/><path class="s55v9q0hw"/><path class="c5ipzfbmx"/><path class="d8abqfbpc"/><path class="fu2iodbya"/><path class="r_-onzaex"/><path class="gv9l4p83m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gale-duotone-bold" {...props}></Icon>
<style>
:global(.c5ipzfbmx) {
  d: path("M3 6h16");
}

:global(.d8abqfbpc) {
  d: path("M3 11h18");
}

:global(.dqwni1b6f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fu2iodbya) {
  d: path("M3 16h16");
}

:global(.g55pkgb9q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gv9l4p83m) {
  d: path("m21 19 -3 3");
}

:global(.r_-onzaex) {
  d: path("m16 19 -3 3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s55v9q0hw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m21 19 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w9o11dbmt) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 19 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z5rak8b7e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
