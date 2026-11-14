<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fcbjjpr7j"/><path class="lh606zbet"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bypass" {...props}></Icon>
<style>
:global(.fcbjjpr7j) {
  d: path("m4 12.5l4-4l4 4v6H4Zm10 9c0-3.5 5.5-4.5 5.5-9S14 7 14 3.5");
}

:global(.lh606zbet) {
  d: path("M11.5 6L14 3.5L16.5 6M8 18.5v-3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
