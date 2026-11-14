<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k15yz01bh"/><path class="h0kwjcc3e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:priority-low" {...props}></Icon>
<style>
:global(.h0kwjcc3e) {
  d: path("M10 10.5h4v10h-4Zm7-7h4v17h-4Z");
}

:global(.k15yz01bh) {
  fill: currentColor;
  d: path("M3 16.5h4v4H3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
