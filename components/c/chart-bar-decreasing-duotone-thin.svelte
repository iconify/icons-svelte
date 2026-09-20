<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="vsycc16wb"/><path class="sl8osqjdc"/><path class="xmhspdw5u"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="xeoeqgblt"/><path class="yw-dgs_nk"/><path class="vjfpd3ony"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chart-bar-decreasing-duotone-thin" {...props}></Icon>
<style>
:global(.gms_xv68n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.sl8osqjdc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vjfpd3ony) {
  d: path("M4 17h6");
}

:global(.vsycc16wb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 7h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xeoeqgblt) {
  d: path("M4 7h14");
}

:global(.xmhspdw5u) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 17h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yu-j7jb_g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yw-dgs_nk) {
  d: path("M4 12h10");
}

</style>
