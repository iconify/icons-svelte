<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="usy_56bxf"/><path class="pvno39b9e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:falling-rocks-sign" {...props}></Icon>
<style>
:global(.pvno39b9e) {
  fill: currentColor;
  d: path("M11 11a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm1.75 4.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.usy_56bxf) {
  d: path("m12 3l9.5 17h-19ZM6.25 13.25L12.5 20");
}

</style>
