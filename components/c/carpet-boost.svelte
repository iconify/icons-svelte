<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r_8qwlbyl"/><path class="uz7xebdng"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:carpet-boost" {...props}></Icon>
<style>
:global(.r_8qwlbyl) {
  d: path("M4.5 11.5h15v9h-15Zm0-3l7.5-5l7.5 5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uz7xebdng) {
  d: path("M7.25 14.25h9.5v3.5h-9.5ZM4.5 13h-2m2 3h-2m2 3h-2m17-6h2m-2 3h2m-2 3h2");
}

</style>
