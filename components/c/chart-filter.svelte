<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eso81_b5r"/><path class="jbh0a07ga"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chart-filter" {...props}></Icon>
<style>
:global(.eso81_b5r) {
  d: path("M3.5 3v17.5h10.7");
}

:global(.jbh0a07ga) {
  d: path("M6.5 14L10 8.5l3 2.5l6-6.5M14.5 15h7L19 18.25v3.25l-2-1v-2.25Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
