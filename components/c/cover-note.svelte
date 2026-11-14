<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nngizebsx"/><path class="dwk2gcb3m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cover-note" {...props}></Icon>
<style>
:global(.dwk2gcb3m) {
  d: path("M19.5 15h-4a1.5 1.5 0 0 0-1.5 1.5v4M8 9h8m-8 4h5");
}

:global(.nngizebsx) {
  d: path("M4.5 4.5h15V15L14 20.5H4.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
