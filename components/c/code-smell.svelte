<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jgy-5pbrl"/><path class="d7e8oeb0e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:code-smell" {...props}></Icon>
<style>
:global(.d7e8oeb0e) {
  d: path("M8.25 7L6 9.5L8.25 12m3.5-5L14 9.5L11.75 12m4.75 9.75c-1.75-2.25 1.75-5.5 0-7.75m4 7.75c-1.75-2.25 1.75-5.5 0-7.75");
}

:global(.jgy-5pbrl) {
  d: path("M13.3 19.5H3v-17h14v7.6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
