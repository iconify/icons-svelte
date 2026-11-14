<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ln_5g-myc"/><path class="dmnm-sbpk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:prescription-sent" {...props}></Icon>
<style>
:global(.dmnm-sbpk) {
  d: path("M6.25 16.5V9.75H8.5c1 0 1.75.75 1.75 1.75s-.75 1.75-1.75 1.75H6.25m2.25 0l2.518 2.711m.732-2.461l-2.5 3.25m4.5 1l7.25-3.5l-3.25 7l-1.25-2.5Zm7.25-3.5l-4.5 4.5");
}

:global(.ln_5g-myc) {
  d: path("M9.1 19H3V2.5h13v11.1M6 6.5h7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
