<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rim4hghxu"/><path class="qtswku02i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:element-antimony" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qtswku02i) {
  d: path("m8.01 9.577l1.041-2.5A1.75 1.75 0 0 1 10.667 6h2.666a1.75 1.75 0 0 1 1.616 1.077l1.041 2.5A1.75 1.75 0 0 1 14.375 12h-4.75A1.75 1.75 0 0 1 8.01 9.577");
}

:global(.rim4hghxu) {
  d: path("m3.51 15.577l1.041-2.5A1.75 1.75 0 0 1 6.167 12h11.666a1.75 1.75 0 0 1 1.616 1.077l1.041 2.5A1.75 1.75 0 0 1 18.875 18H5.125a1.75 1.75 0 0 1-1.615-2.423");
}

</style>
