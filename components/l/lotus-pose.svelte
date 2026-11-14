<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o0l_gcbcf"/><path class="furctvmvp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lotus-pose" {...props}></Icon>
<style>
:global(.furctvmvp) {
  d: path("M3 18.5c3-4 15-4 18 0c-3 3.5-15 3.5-18 0Z");
}

:global(.o0l_gcbcf) {
  d: path("M9.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM5.75 16.5l2.75-6h7l2.75 6m-6.25-6v5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
