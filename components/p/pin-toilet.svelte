<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nm66_ccwr"/><path class="do16zub0f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pin-toilet" {...props}></Icon>
<style>
:global(.do16zub0f) {
  fill: currentColor;
  d: path("M7.5 6h.01");
}

:global(.nm66_ccwr) {
  d: path("M4.5 3h6v8.5h-6ZM4 11.5h16c0 3.5-2.5 5.5-6 6l1 3.5H8l.5-4c-3-1-4.5-3-4.5-5.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
