<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jg087qttg"/><path class="heagg9bky"/><path class="l9j0qbc6t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:email-coupon" {...props}></Icon>
<style>
:global(.heagg9bky) {
  d: path("m2.5 11l9.5 6l9.5-6");
}

:global(.jg087qttg) {
  d: path("M2.5 11v8a2 2 0 0 0 2 2h15a2 2 0 0 0 2-2v-8");
}

:global(.l9j0qbc6t) {
  d: path("M6.5 13.5v-4a1.5 1.5 0 0 0 0-3V3h11v3.5a1.5 1.5 0 0 0 0 3v4M10 11l4-4.5m-4 0h.01M14 11h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
