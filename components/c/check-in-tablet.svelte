<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p6pi3ioed"/><path class="r43agud4t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:check-in-tablet" {...props}></Icon>
<style>
:global(.p6pi3ioed) {
  d: path("M6 2.5h12v15H6Zm3 19h6m-3-4v4");
}

:global(.r43agud4t) {
  d: path("m9 10.25l2.25 2.25L15 8.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
