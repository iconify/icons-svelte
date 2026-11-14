<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g4korjm9s"/><path class="bm0ufeg4h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:electrical-plan" {...props}></Icon>
<style>
:global(.bm0ufeg4h) {
  d: path("m19 14l-4 4.75h3L17 22l4-5h-3Z");
}

:global(.g4korjm9s) {
  d: path("M9.5 21H3V3h18v11.2M12 3v6m0 4v5m-9-6h5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
