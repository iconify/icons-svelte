<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wdsipzehx"/><path class="ko6u8tbst"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:keyboard-check" {...props}></Icon>
<style>
:global(.ko6u8tbst) {
  d: path("M9.5 14.25L11.25 16l3.25-3.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wdsipzehx) {
  d: path("M2 6h20v12H2Zm4 3.25h.01m3.99 0h.01m3.99 0h.01m3.99 0h.01");
}

</style>
