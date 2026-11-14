<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="agabj8kal"/><path class="vyz_p21cv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:on-call" {...props}></Icon>
<style>
:global(.agabj8kal) {
  d: path("M3 8.5h13.5v11H3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vyz_p21cv) {
  d: path("M5.5 11H14v3.5H5.5Zm4.25 6h.01M16 5.75a2.75 2.75 0 0 1 2.75 2.75M16 3a5.5 5.5 0 0 1 5.5 5.5");
}

</style>
