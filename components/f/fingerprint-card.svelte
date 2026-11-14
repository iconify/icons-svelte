<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o0uxpabcc"/><path class="jtj_88b2u"/><path class="mvqhc34is"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fingerprint-card" {...props}></Icon>
<style>
:global(.jtj_88b2u) {
  d: path("M7.5 14v-3a4.5 4.5 0 0 1 9 0v1.5");
}

:global(.mvqhc34is) {
  d: path("M10.25 14.5V11a1.75 1.75 0 0 1 3.5 0v3.5M7.5 17.75h9");
}

:global(.o0uxpabcc) {
  d: path("M2.5 3.5h19v17h-19Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
