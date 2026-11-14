<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b6fis-_bt"/><path class="ktzk7nbkm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:aspect-ratio-4-3" {...props}></Icon>
<style>
:global(.b6fis-_bt) {
  d: path("M3 5.25h18v13.5H3Z");
}

:global(.ktzk7nbkm) {
  d: path("M6.25 11V8.25h3m8.5 4.75v2.75h-3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
