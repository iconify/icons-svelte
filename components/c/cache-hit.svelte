<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qpgwjk3fm"/><path class="w6ps69hvf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cache-hit" {...props}></Icon>
<style>
:global(.qpgwjk3fm) {
  d: path("M11.653 18.924L10.5 19.5l-8-4v-9l8-4l8 4v7.856");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w6ps69hvf) {
  d: path("m2.5 6.5l8 4l8-4m-8 4v9m-4-15l8 4m.25 9.5l2 2L21 15.75");
}

</style>
