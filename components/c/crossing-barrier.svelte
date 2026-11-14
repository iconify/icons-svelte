<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nkis0bbjq"/><path class="jgtwt8jrc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:crossing-barrier" {...props}></Icon>
<style>
:global(.jgtwt8jrc) {
  d: path("m8.375 11.659l9.576-8.034L20.2 6.306l-9.575 8.035Zm3.447-2.892l2.25 2.681m.814-5.252l2.25 2.681");
}

:global(.nkis0bbjq) {
  d: path("M5.5 11h4v10.5h-4Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
