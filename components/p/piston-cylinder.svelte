<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x-xvdcc7d"/><path class="k_cro8zpl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:piston-cylinder" {...props}></Icon>
<style>
:global(.k_cro8zpl) {
  d: path("M5 11h14v3H5Zm3.5-8.5h7m-3.5 0V11");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x-xvdcc7d) {
  d: path("M5 5v14a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V5");
}

</style>
