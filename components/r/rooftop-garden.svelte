<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tdtq1_bim"/><path class="spcboybbm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:rooftop-garden" {...props}></Icon>
<style>
:global(.spcboybbm) {
  d: path("M10 21.5v-4h4v4M12 12V5.5M12 9c0-3-2-4.5-5-4.5C7 7.5 9 9 12 9Zm0-1.5c0-3 2-4.5 5-4.5c0 3-2 4.5-5 4.5Z");
}

:global(.tdtq1_bim) {
  d: path("M4 12h16v9.5H4Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
