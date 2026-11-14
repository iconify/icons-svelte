<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t3gv10b3e"/><path class="hjeuxo3vf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:category-cycling" {...props}></Icon>
<style>
:global(.hjeuxo3vf) {
  d: path("m6 16l4-8h6l2 8m-8-8L8.5 5.5h3");
}

:global(.t3gv10b3e) {
  d: path("M2 16a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm12 0a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
