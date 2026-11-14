<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="emztpiq7b"/><path class="k_uvbf3mb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cereal-bar-pack" {...props}></Icon>
<style>
:global(.emztpiq7b) {
  d: path("M3 4.5h18l-1.5 3.75L21 12l-1.5 3.75L21 19.5H3l1.5-3.75L3 12l1.5-3.75Z");
}

:global(.k_uvbf3mb) {
  d: path("M7.5 7.25h9v3h-9Zm0 6.5h9v3h-9Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
