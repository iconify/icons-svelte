<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gh-eohwic"/><path class="ou3dmzb7p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:nuclear-fusion" {...props}></Icon>
<style>
:global(.gh-eohwic) {
  d: path("M6 12a3.75 3.75 0 1 0 7.5 0A3.75 3.75 0 1 0 6 12Z");
}

:global(.ou3dmzb7p) {
  d: path("M10.5 12a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0ZM3.75 5.25l1.5 1.5m15-1.5l-1.5 1.5m-15 12l1.5-1.5m15 1.5l-1.5-1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
