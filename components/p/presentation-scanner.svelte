<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dqdio1brg"/><path class="n51xz8c5b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:presentation-scanner" {...props}></Icon>
<style>
:global(.dqdio1brg) {
  d: path("M10 2.5h11.5v10H10Zm5.75 10V19M12 19h7.5v2.5H12Z");
}

:global(.n51xz8c5b) {
  d: path("M12.75 5h5.5v5h-5.5ZM8 5L2.5 3.5m5.5 4H2.5M8 10l-5.5 1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
