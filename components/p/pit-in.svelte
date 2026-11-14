<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xgp7uacfz"/><path class="fzuvp1brt"/><path class="smi5gzb5e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pit-in" {...props}></Icon>
<style>
:global(.fzuvp1brt) {
  d: path("M4.5 2.5h5A3.5 3.5 0 0 1 13 6v10.5");
}

:global(.smi5gzb5e) {
  d: path("M10.25 13.75L13 16.5l2.75-2.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xgp7uacfz) {
  d: path("M7 10h12v11.5H7Z");
}

</style>
