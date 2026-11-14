<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sxnh-zzrn"/><path class="i3e_gmufr"/><path class="cdxjicbsp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:refresh-ccw" {...props}></Icon>
<style>
:global(.cdxjicbsp) {
  d: path("m15.5 15l3-3l3 3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i3e_gmufr) {
  d: path("m2.5 9l3 3l3-3m10 3a6.5 6.5 0 0 1-12.129 3.25");
}

:global(.sxnh-zzrn) {
  d: path("M5.5 12a6.5 6.5 0 0 1 12.129-3.25");
}

</style>
