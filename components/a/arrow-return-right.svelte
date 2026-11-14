<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uh0j-mlwd"/><path class="xj4tptb9e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:arrow-return-right" {...props}></Icon>
<style>
:global(.uh0j-mlwd) {
  d: path("M15 5.5H9.5a4.5 4.5 0 0 0 0 9h10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xj4tptb9e) {
  d: path("m15.5 10.5l4 4l-4 4");
}

</style>
