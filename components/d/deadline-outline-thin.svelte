<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oe2u-obal"/><path class="u4_zcfcdm"/><path class="qaaffjxln"/><path class="fhbl5kbmk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:deadline-outline-thin" {...props}></Icon>
<style>
:global(.fhbl5kbmk) {
  d: path("M21 3v18");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oe2u-obal) {
  d: path("M12.96 5.66a7 7 0 1 1 -5.92 0");
}

:global(.qaaffjxln) {
  d: path("M10 12h5");
}

:global(.u4_zcfcdm) {
  d: path("M10 7v5");
}

</style>
