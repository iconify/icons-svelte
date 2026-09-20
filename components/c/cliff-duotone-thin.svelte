<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q6zbhsh2k"/><path class="n2-eu36vv"/><path class="ior14cbcm"/><path class="hr8ceclju"/><path class="rn2_dtbur"/><path class="ubbszwy6j"/><path class="z9ittvbis"/><path class="a562fv74t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cliff-duotone-thin" {...props}></Icon>
<style>
:global(.a562fv74t) {
  d: path("M6 22h12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hr8ceclju) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 22h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ior14cbcm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n2-eu36vv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m13 8 4 4v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q6zbhsh2k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 3h10v13H3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rn2_dtbur) {
  d: path("M3 3h10v13H3");
}

:global(.ubbszwy6j) {
  d: path("m13 8 4 4v4");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
