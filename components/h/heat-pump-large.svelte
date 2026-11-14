<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vtv3qiybn"/><path class="a09vmcbkm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:heat-pump-large" {...props}></Icon>
<style>
:global(.a09vmcbkm) {
  d: path("M5.25 10.25a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm2-2l4 4m0-4l-4 4m10-6c-1.25 1.25-1.25 2.5 0 4s1.25 2.75 0 4M6 17v3.5M18 17v3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vtv3qiybn) {
  d: path("M2.5 3.5h19V17h-19Z");
}

</style>
