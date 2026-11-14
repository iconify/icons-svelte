<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d6aam1rah"/><path class="wi6nhb2cd"/><path class="wqdx-yb5k"/><path class="p9w4xwa0a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cricket-spin" {...props}></Icon>
<style>
:global(.d6aam1rah) {
  d: path("M7.5 12a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

:global(.p9w4xwa0a) {
  d: path("M15 6h3V3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wi6nhb2cd) {
  d: path("M9 8.5c2.5 2 2.5 5 0 7");
}

:global(.wqdx-yb5k) {
  d: path("M4.75 16.25A8.5 8.5 0 0 1 18 6");
}

</style>
