<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dpwrr4bif"/><path class="sccd98btk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ancestral-tablet" {...props}></Icon>
<style>
:global(.dpwrr4bif) {
  d: path("M6.5 18.5v-13q5.5-3.5 11 0v13m-13 3l2-3h11l2 3Z");
}

:global(.sccd98btk) {
  d: path("M9.25 6.75h5.5v9h-5.5ZM12 9.5V13");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
