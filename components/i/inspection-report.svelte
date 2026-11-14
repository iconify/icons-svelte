<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i9goxbc4n"/><path class="j4_i6obxf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:inspection-report" {...props}></Icon>
<style>
:global(.i9goxbc4n) {
  d: path("M4.5 2.5h15v19h-15Zm2.25 2.25v2m0 10.5v2");
}

:global(.j4_i6obxf) {
  d: path("m9 7.5l1 1l2-2m1.75 1h2.75M9 12l1 1l2-2m1.75 1h2.75M9 16.5l1 1l2-2m1.75 1h2.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
