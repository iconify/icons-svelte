<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iizzxacfc"/><path class="bt0m92p7j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mask-privacy" {...props}></Icon>
<style>
:global(.bt0m92p7j) {
  d: path("M5.25 11a2.25 1.5 0 1 0 4.5 0a2.25 1.5 0 1 0-4.5 0Zm9 0a2.25 1.5 0 1 0 4.5 0a2.25 1.5 0 1 0-4.5 0Z");
}

:global(.iizzxacfc) {
  d: path("M2.5 9c0-1.5 1-2.5 2.5-2.5h14c1.5 0 2.5 1 2.5 2.5v2c0 3.5-2.5 5.5-5.5 5.5c-2 0-3-1.5-4-2.5c-1 1-2 2.5-4 2.5c-3 0-5.5-2-5.5-5.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
