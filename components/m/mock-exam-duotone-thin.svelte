<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fqapklbmg"/><path class="eyyyeghth"/><path class="r182r524c"/><path class="r_4k1sbsg"/><path class="zwgz_-bzc"/><path class="ivxatgkif"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mock-exam-duotone-thin" {...props}></Icon>
<style>
:global(.eyyyeghth) {
  d: path("M4 3h16v18H4Z");
}

:global(.fqapklbmg) {
  fill: currentColor;
  d: path("M4 3h16v18H4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ivxatgkif) {
  d: path("m19 15 -6 6");
}

:global(.r_4k1sbsg) {
  d: path("M7 13h6");
}

:global(.r182r524c) {
  d: path("M7 9h10");
}

:global(.zwgz_-bzc) {
  d: path("m13 15 6 6");
}

</style>
