<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mxu4iwysg"/><path class="nii_ngb3a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:gantt-baseline" {...props}></Icon>
<style>
:global(.mxu4iwysg) {
  d: path("M3.5 3v18m3-16H17v5H6.5Z");
}

:global(.nii_ngb3a) {
  fill: currentColor;
  d: path("M10.5 13.5H21v5H10.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
