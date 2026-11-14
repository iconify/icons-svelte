<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mdhcsi96i"/><path class="ju8iambde"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:paintbrush" {...props}></Icon>
<style>
:global(.ju8iambde) {
  d: path("m9.5 11l3.5 3.5c-.5 4-5.5 6.5-10 6.5c0-4.5 2.5-9.5 6.5-10Zm4.25-.75L20.5 3.5");
}

:global(.mdhcsi96i) {
  d: path("m12 8.5l3.5 3.5l-2.5 2.5L9.5 11Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
