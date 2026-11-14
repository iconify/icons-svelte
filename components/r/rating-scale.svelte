<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ugiss7l0k"/><path class="oexsrccxy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:rating-scale" {...props}></Icon>
<style>
:global(.oexsrccxy) {
  fill: currentColor;
  d: path("M7.75 14L6.5 20l5.5-3l5.5 3l-1.25-6Z");
}

:global(.ugiss7l0k) {
  d: path("m12 3.25l2.645 5.609l6.152.783l-4.517 4.249l1.157 6.092L12 17l-5.437 2.983l1.157-6.092l-4.517-4.249l6.152-.783Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
