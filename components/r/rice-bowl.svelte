<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="weauatble"/><path class="gjbgv3vom"/><path class="w9_pe4mbd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:rice-bowl" {...props}></Icon>
<style>
:global(.gjbgv3vom) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 10.75a7 6.5 0 0 1 14 0");
}

:global(.w9_pe4mbd) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 7.75h.01m4.99 0h.01");
}

:global(.weauatble) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 10.75h16a.75.75 0 0 1 .75.8A8.75 8.75 0 0 1 16 18.7v1.55a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1V18.7a8.75 8.75 0 0 1-4.75-7.15a.75.75 0 0 1 .75-.8");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
