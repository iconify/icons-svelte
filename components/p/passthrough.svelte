<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ei_n13-2k"/><path class="q9hi0t1-l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:passthrough" {...props}></Icon>
<style>
:global(.ei_n13-2k) {
  d: path("M7 5h10a4 4 0 0 1 4 4v5a4 4 0 0 1-4 4h-2.5L12 15.5L9.5 18H7a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4Zm5 3v4.5");
}

:global(.q9hi0t1-l) {
  d: path("m6.5 14.5l5.5-2l5.5 2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
