<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tr-t3t6bj"/><path class="a7290z_hy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:evacuation-plan" {...props}></Icon>
<style>
:global(.a7290z_hy) {
  d: path("m3.5 11l2-1.75L8 9l2.75 2.25M16.25 9L19 12l-2.75 3");
}

:global(.tr-t3t6bj) {
  d: path("M13.5 2.5h8.25v19H13.5ZM7 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM8 9l-1.5 5l3 3v4m-3-7l-1.75 4l-2.25 1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
