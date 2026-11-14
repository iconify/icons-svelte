<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="adqmrhm1q"/><path class="klplchb9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:awareness-survey" {...props}></Icon>
<style>
:global(.adqmrhm1q) {
  d: path("M4.5 3.5h15v18h-15Z");
}

:global(.klplchb9b) {
  d: path("M8.5 2h7v3h-7Zm-1 7l1.25 1l2-2M7.5 13.5l1.25 1l2-2M7.5 18l1.25 1l2-2m2.5-8h3.25m-3.25 4.5h3.25M13.25 18h3.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
