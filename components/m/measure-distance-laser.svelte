<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l6u_nifpu"/><path class="xwhxajbvv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:measure-distance-laser" {...props}></Icon>
<style>
:global(.l6u_nifpu) {
  d: path("M2.5 5H11v14H2.5Zm19 0v9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xwhxajbvv) {
  d: path("M5.25 7.75h3v3.5h-3ZM11 9.5h3.25m2.75 0h4.5");
}

</style>
