<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="venoiz-zq"/><path class="jllohdbyn"/><path class="js0mhwyps"/><path class="qye9c0bkv"/><path class="vspm3ybjo"/><path class="qcxa0jb0g"/><path class="a3eibhdgt"/><path class="z26gfvqcs"/><path class="odwdycbcr"/><path class="f-6kshnwt"/><path class="g7e-mbajx"/><path class="k7llgzrde"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pet-cover-duotone-bold" {...props}></Icon>
<style>
:global(.a3eibhdgt) {
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
}

:global(.f-6kshnwt) {
  d: path("M11 12.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.g7e-mbajx) {
  d: path("M15 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.jllohdbyn) {
  fill: currentColor;
  d: path("M11 12.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.js0mhwyps) {
  fill: currentColor;
  d: path("M15 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.k7llgzrde) {
  d: path("M10 18.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.odwdycbcr) {
  d: path("M7 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.qcxa0jb0g) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4.5 9.5h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qye9c0bkv) {
  fill: currentColor;
  d: path("M10 18.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.venoiz-zq) {
  fill: currentColor;
  d: path("M7 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vspm3ybjo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z26gfvqcs) {
  d: path("M4.5 9.5h15");
}

</style>
