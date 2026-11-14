<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e-9dgdkyt"/><path class="j7ztdacox"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chat-double" {...props}></Icon>
<style>
:global(.e-9dgdkyt) {
  d: path("M3 9a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v5.5a2 2 0 0 1-2 2H8.5l-3 3v-3H5a2 2 0 0 1-2-2Z");
}

:global(.j7ztdacox) {
  d: path("M9 7V5.5a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2h-4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
