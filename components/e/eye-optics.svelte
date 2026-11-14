<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cmvr_w51t"/><path class="rqt4nqb8n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:eye-optics" {...props}></Icon>
<style>
:global(.cmvr_w51t) {
  d: path("M2.5 9C4 5.25 6.6 3 9.75 3S15.5 5.25 17 9c-1.5 3.75-4.1 6-7.25 6S4 12.75 2.5 9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rqt4nqb8n) {
  d: path("M6.75 9a3 3 0 1 0 6 0a3 3 0 1 0-6 0M19 14.5a4 4 0 0 1 0 7a4 4 0 0 1 0-7M15.5 18h6");
}

</style>
