<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_84f4bvu"/><path class="id4-i3bwx"/><path class="t3y19xb5z"/><path class="p8vnfob_b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fat-bike" {...props}></Icon>
<style>
:global(.id4-i3bwx) {
  d: path("M5.5 15.5H12l4-6l2.5 6");
}

:global(.j_84f4bvu) {
  d: path("M2 15.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm13 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

:global(.p8vnfob_b) {
  d: path("M4 15.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm13 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.t3y19xb5z) {
  d: path("m5.5 15.5l5-6H16m-4 6l-2-8m-1.5 0h3m4.5 2L15 7h2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
