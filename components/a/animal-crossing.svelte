<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dh2jzoboc"/><path class="bh4j4-b9d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:animal-crossing" {...props}></Icon>
<style>
:global(.bh4j4-b9d) {
  d: path("M8.5 16v-3h5v3m0-3L15 9.25h1.5m-1.5 0l-.75-2.5");
}

:global(.dh2jzoboc) {
  d: path("m12 2l10 10l-10 10L2 12Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
