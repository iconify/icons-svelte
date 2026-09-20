<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qz_by4b2x"/><path class="gc9dmfy3u"/><path class="zzazs-rvi"/><path class="ll_i_4bra"/><path class="ud-rllqqn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:model-fork-outline-thin" {...props}></Icon>
<style>
:global(.gc9dmfy3u) {
  d: path("m10.5 7.5 -5 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ll_i_4bra) {
  d: path("M2.5 14.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.qz_by4b2x) {
  d: path("m12 4 2.5 2.5L12 9 9.5 6.5Z");
}

:global(.ud-rllqqn) {
  d: path("M17.5 14.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.zzazs-rvi) {
  d: path("m13.5 7.5 5 5");
}

</style>
