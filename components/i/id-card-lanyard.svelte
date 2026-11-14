<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s5kdvu5xh"/><path class="bxxlnq37o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:id-card-lanyard" {...props}></Icon>
<style>
:global(.bxxlnq37o) {
  d: path("M6.25 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-.75 6.5c0-1.25 1.1-2 2.5-2s2.5.75 2.5 2m3-6.5h5m-5 4H17");
}

:global(.s5kdvu5xh) {
  d: path("M2.5 7.5h19v14h-19Zm7 0V5.25a2.5 2.5 0 0 1 5 0V7.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
