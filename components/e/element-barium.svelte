<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ry86ptbio"/><path class="xvcd41brn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:element-barium" {...props}></Icon>
<style>
:global(.ry86ptbio) {
  d: path("M3 6h18v12H3Zm6 0v12m6-12v12M3 12h18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xvcd41brn) {
  fill: currentColor;
  d: path("M9 6h6v6H9Z");
}

</style>
