<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vqxtnkbkf"/><path class="nyxw1pb5f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:house-water" {...props}></Icon>
<style>
:global(.nyxw1pb5f) {
  d: path("M18 14.5s-2.75 3-2.75 4.5a2.75 2.75 0 0 0 5.5 0c0-1.5-2.75-4.5-2.75-4.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vqxtnkbkf) {
  d: path("M12.644 20.5H3.5v-10L12 3.25l8.5 7.25v2.656");
}

</style>
