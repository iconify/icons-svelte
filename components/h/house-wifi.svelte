<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="azugnvbfp"/><path class="lft9d5bss"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:house-wifi" {...props}></Icon>
<style>
:global(.azugnvbfp) {
  d: path("M4.5 14L12 9l7.5 5v7.5h-15Z");
}

:global(.lft9d5bss) {
  d: path("M10 21.5v-4h4v4M9.879 6.879a3 3 0 0 1 4.242 0M7.404 4.404a6.5 6.5 0 0 1 9.192 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
