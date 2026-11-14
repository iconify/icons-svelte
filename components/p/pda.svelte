<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r8m762e4d"/><path class="y__wl9brl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pda" {...props}></Icon>
<style>
:global(.r8m762e4d) {
  d: path("M2.5 2.5H15v19H2.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y__wl9brl) {
  d: path("M5.5 5.5H12V12H5.5Zm1.75 11a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM21 3.5l-3 17");
}

</style>
