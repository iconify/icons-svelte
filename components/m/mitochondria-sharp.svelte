<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kzjr49bkc"/><path class="twc8jcbyw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mitochondria-sharp" {...props}></Icon>
<style>
:global(.kzjr49bkc) {
  d: path("M3 12c0-3.25 2.5-5.5 6-5.5c1.5 0 2.25.75 3 .75s1.5-.75 3-.75c3.5 0 6.25 2.25 6.25 5.5S17.5 17.5 12 17.5S3 15.25 3 12Z");
}

:global(.twc8jcbyw) {
  d: path("M5.75 12C7 9.5 8.25 9.5 9 12s2 2.5 3.25 0s2-2.5 3.25 0s2 2.5 3.25 0");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
