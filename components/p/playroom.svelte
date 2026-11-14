<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wky9r-s-h"/><path class="mgfzucbpu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:playroom" {...props}></Icon>
<style>
:global(.mgfzucbpu) {
  d: path("M5.25 17.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm9.5 2l2-4l2 4Zm-5-8.25L12 5.75L14.25 11m-3.5-2h2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wky9r-s-h) {
  d: path("M2.5 13H12v8.5H2.5Zm9.5 0h9.5v8.5H12ZM7.25 3.5h9.5V13h-9.5Z");
}

</style>
