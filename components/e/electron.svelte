<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bexm6iwui"/><path class="xqafg3_uv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:electron" {...props}></Icon>
<style>
:global(.bexm6iwui) {
  d: path("M4.25 16.5a9 5-30 1 1 15.5-9a9 5-30 1 1-15.5 9Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xqafg3_uv) {
  fill: currentColor;
  d: path("M17.75 7.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
