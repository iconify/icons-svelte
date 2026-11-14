<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h8kbv2r-h"/><path class="h-q9ncc-m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:desk-assignment" {...props}></Icon>
<style>
:global(.h-q9ncc-m) {
  d: path("M10.5 7.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.h8kbv2r-h) {
  d: path("M2.5 15h19m-17 0v6m15-6v6M12 15s-4.75-4-4.75-7.25a4.75 4.75 0 0 1 9.5 0C16.75 11 12 15 12 15Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
