<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xvra06v5i"/><path class="uji0smbln"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ram" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uji0smbln) {
  d: path("M6.5 9.5zA1.5 1.5 0 0 1 8 11a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 5 11a1.5 1.5 0 0 1 1.5-1.5m5.5 0za1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 12 9.5m5.5 0zA1.5 1.5 0 0 1 19 11a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 16 11a1.5 1.5 0 0 1 1.5-1.5m-12 6v3m3-3v3m7-3v3m3-3v3");
}

:global(.xvra06v5i) {
  d: path("M4.625 6.5h14.75A2.625 2.625 0 0 1 22 9.125v3.75a2.625 2.625 0 0 1-2.625 2.625H4.625A2.625 2.625 0 0 1 2 12.875v-3.75A2.625 2.625 0 0 1 4.625 6.5");
}

</style>
