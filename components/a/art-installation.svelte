<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ukdudugbn"/><path class="nzqy8b1bz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:art-installation" {...props}></Icon>
<style>
:global(.nzqy8b1bz) {
  d: path("M5.75 13.25L8 9.5L9.25 11");
}

:global(.ukdudugbn) {
  d: path("M3 5h9v11H3Zm12 0h6.5v8H15ZM2.5 19.5h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
