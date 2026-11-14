<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y4qb67hob"/><path class="pan3f_chh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bootcamp" {...props}></Icon>
<style>
:global(.pan3f_chh) {
  d: path("M5.5 11.5c-3-5.5-.5-9 4-9S15.5 6 13 10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y4qb67hob) {
  d: path("M9 10h11.5v5H14a5 5 0 1 1-5-5Z");
}

</style>
