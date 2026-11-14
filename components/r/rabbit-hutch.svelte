<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wlxb561rh"/><path class="i1o89f13j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:rabbit-hutch" {...props}></Icon>
<style>
:global(.i1o89f13j) {
  d: path("M9.5 17.5v-4a2.5 2.5 0 0 1 5 0v4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wlxb561rh) {
  d: path("m3.5 8l17-4v13.5h-17ZM6 17.5V21m12-3.5V21");
}

</style>
