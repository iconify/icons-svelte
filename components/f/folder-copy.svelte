<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xo_ra0b-c"/><path class="arg1lfbec"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:folder-copy" {...props}></Icon>
<style>
:global(.arg1lfbec) {
  d: path("M3.5 17V5.5A1.5 1.5 0 0 1 5 4h3l1.5 1.5H16");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xo_ra0b-c) {
  d: path("M7 10a1.5 1.5 0 0 1 1.5-1.5h3L13 10h6.5a1.5 1.5 0 0 1 1.5 1.5V19a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 7 19Z");
}

</style>
