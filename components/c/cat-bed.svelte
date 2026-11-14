<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y1jse2nxo"/><path class="og1t_xayx"/><path class="qaj-sobli"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cat-bed" {...props}></Icon>
<style>
:global(.og1t_xayx) {
  d: path("M2.5 10.5v3a9.5 5 0 0 0 19 0v-3");
}

:global(.qaj-sobli) {
  d: path("M7 10a5 1.75 0 1 0 10 0a5 1.75 0 1 0-10 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y1jse2nxo) {
  d: path("M2.5 10.5a9.5 5 0 1 0 19 0a9.5 5 0 1 0-19 0Z");
}

</style>
