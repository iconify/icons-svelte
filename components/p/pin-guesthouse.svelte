<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x9omiybac"/><path class="h4p2jqpsn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pin-guesthouse" {...props}></Icon>
<style>
:global(.h4p2jqpsn) {
  d: path("M7 17h10v3.5M7 14h8.5a1.5 1.5 0 0 1 1.5 1.5V17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x9omiybac) {
  d: path("M3.5 10.5L12 3.25l8.5 7.25v10h-17Zm3.5 2v8");
}

</style>
