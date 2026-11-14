<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mijt3ob_z"/><path class="cx9tvzb3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:frame-clip-content" {...props}></Icon>
<style>
:global(.cx9tvzb3z) {
  d: path("M9.55 9.55a7 7 0 0 1 4.34-2.023m3.568.629a7 7 0 0 1 3.386 3.386m.629 3.568a7 7 0 0 1-2.023 4.34");
}

:global(.mijt3ob_z) {
  d: path("M2.5 2.5h12v12h-12Zm12 19a7 7 0 0 1-7-7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
