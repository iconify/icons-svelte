<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fr82svbdj"/><path class="x3n083g2c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:podcast-feed" {...props}></Icon>
<style>
:global(.fr82svbdj) {
  d: path("M4.5 19.5h.01m-.01-6a6 6 0 0 1 6 6m-6-11a11 11 0 0 1 11 11");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x3n083g2c) {
  d: path("M4.5 3.5a16 16 0 0 1 16 16");
}

</style>
