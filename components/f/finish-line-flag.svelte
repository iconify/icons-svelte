<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q6box_btg"/><path class="dcox06bxm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:finish-line-flag" {...props}></Icon>
<style>
:global(.dcox06bxm) {
  fill: currentColor;
  d: path("M5 3.5h7.25v5H5Zm7.25 5h7.25v5h-7.25Z");
}

:global(.q6box_btg) {
  d: path("M5 2.5v19m0-18h14.5v10H5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
