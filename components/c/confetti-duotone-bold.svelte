<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="eoow0nb0s"/><path class="aa6mzfbty"/><path class="i78exbcto"/><path class="r39nb1euw"/><path class="bt8odmbat"/><path class="mr78hnbrx"/><path class="r-0o544te"/><path class="pfvjrtb4r"/><path class="p59zvybqt"/><path class="nk-dq3bmo"/><path class="som9nz4hy"/><path class="k04qs_b8d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:confetti-duotone-bold" {...props}></Icon>
<style>
:global(.aa6mzfbty) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bt8odmbat) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 10 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.eoow0nb0s) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 4 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i78exbcto) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m4 13 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k04qs_b8d) {
  d: path("m9 18 3 3");
}

:global(.mr78hnbrx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 18 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nk-dq3bmo) {
  d: path("m16 14 3 3");
}

:global(.p59zvybqt) {
  d: path("m4 13 3 3");
}

:global(.pfvjrtb4r) {
  d: path("m15 5 3 3");
}

:global(.r-0o544te) {
  d: path("m5 4 3 3");
}

:global(.r39nb1euw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m16 14 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.som9nz4hy) {
  d: path("m10 10 3 3");
}

</style>
