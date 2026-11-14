<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="orqm14bpo"/><path class="m4m9i8bnh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:data-bars-cells" {...props}></Icon>
<style>
:global(.m4m9i8bnh) {
  fill: currentColor;
  d: path("M7.5 5h9v1.5h-9Zm0 6.25h4v1.5h-4Zm0 6.25H14V19H7.5Z");
}

:global(.orqm14bpo) {
  d: path("M4.5 2.5h15v19h-15Zm0 6.25h15m-15 6.5h15");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
