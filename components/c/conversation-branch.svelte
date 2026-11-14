<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tftnstbxs"/><path class="h8y6kwivj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:conversation-branch" {...props}></Icon>
<style>
:global(.h8y6kwivj) {
  d: path("M18 11v1a3.5 3.5 0 0 1-3.5 3.5H6");
}

:global(.tftnstbxs) {
  d: path("M4 5.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm0 13a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM16 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM6 7.5v9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
