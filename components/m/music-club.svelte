<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="egsfzqb1r"/><path class="k280clidi"/><path class="hwdp53bns"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:music-club" {...props}></Icon>
<style>
:global(.egsfzqb1r) {
  d: path("M9 2.5V8m-6.5 6.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Z");
}

:global(.hwdp53bns) {
  d: path("M6.5 14.5a2.5 6.5 0 1 0 5 0a2.5 6.5 0 1 0-5 0ZM17 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3 0V2.5");
}

:global(.k280clidi) {
  d: path("M2.5 14.5a6.5 2.5 0 1 0 13 0a6.5 2.5 0 1 0-13 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
