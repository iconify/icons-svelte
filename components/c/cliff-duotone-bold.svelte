<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c9i9zwf-r"/><path class="ky6ccrb_q"/><path class="d5b4fcc2f"/><path class="wotrkdy7x"/><path class="rn2_dtbur"/><path class="ubbszwy6j"/><path class="z9ittvbis"/><path class="a562fv74t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cliff-duotone-bold" {...props}></Icon>
<style>
:global(.a562fv74t) {
  d: path("M6 22h12");
}

:global(.c9i9zwf-r) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 3h10v13H3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d5b4fcc2f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ky6ccrb_q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m13 8 4 4v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rn2_dtbur) {
  d: path("M3 3h10v13H3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ubbszwy6j) {
  d: path("m13 8 4 4v4");
}

:global(.wotrkdy7x) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 22h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
