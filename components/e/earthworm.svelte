<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x9s1xtqjs"/><path class="svciqqb_y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:earthworm" {...props}></Icon>
<style>
:global(.svciqqb_y) {
  d: path("M2.5 19.5H3q5-6 10 0h8.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x9s1xtqjs) {
  d: path("M6.5 16.75V11a4.5 4.5 0 0 1 9 0v1a1.5 1.5 0 0 0 3 0V6.5a1.5 1.5 0 0 1 3 0V12a4.5 4.5 0 0 1-9 0v-1a1.5 1.5 0 0 0-3 0v5.75");
}

</style>
