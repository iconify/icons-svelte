<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="whl0dcc0b"/><path class="i1y2_jbml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:roundabout-exit-left" {...props}></Icon>
<style>
:global(.i1y2_jbml) {
  d: path("M6.5 7.25L4.25 9.5l2.25 2.25M14 14.5a5 5 0 0 1-4-2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.whl0dcc0b) {
  d: path("M14 21.5v-7a5 5 0 1 0-5-5H4.25");
}

</style>
