<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dr8b_wbob"/><path class="gb26_k93p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:media-query" {...props}></Icon>
<style>
:global(.dr8b_wbob) {
  d: path("M2 3.5h20V17H2ZM12 17v3.5m-4 0h8M6.5 10.25h11");
}

:global(.gb26_k93p) {
  d: path("m8.5 8.25l-2 2l2 2m7-4l2 2l-2 2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
