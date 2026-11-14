<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dha-tx3rx"/><path class="tglg5gf6b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:employee-id-card" {...props}></Icon>
<style>
:global(.dha-tx3rx) {
  d: path("M4.5 6.5h15v14h-15ZM10 3h4m-2 0v3.5");
}

:global(.tglg5gf6b) {
  d: path("M10 11.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM8.5 18a3.5 3 0 0 1 7 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
