<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ey69u4bol"/><path class="m5hes0bss"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pin-care-home" {...props}></Icon>
<style>
:global(.ey69u4bol) {
  d: path("M13.923 20H3v-9.5l8.5-7l8.5 7v1.477M11.5 10.5v6m-3-3h6");
}

:global(.m5hes0bss) {
  d: path("m19 22l-2.25-2.75a2.75 2.75 0 1 1 4.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
