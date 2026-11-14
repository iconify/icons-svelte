<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pf-0bccsx"/><path class="reabgpbsb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:database-shard" {...props}></Icon>
<style>
:global(.pf-0bccsx) {
  d: path("M10.5 6A7.5 2.5 0 0 0 3 8.5v10a7.5 2.5 0 0 0 7.5 2.5Zm3-3A7.5 2.5 0 0 1 21 5.5v10a7.5 2.5 0 0 1-7.5 2.5Z");
}

:global(.reabgpbsb) {
  d: path("M3 8.5a7.5 2.5 0 0 0 7.5 2.5m3-3A7.5 2.5 0 0 0 21 5.5m-18 8a7.5 2.5 0 0 0 7.5 2.5m3-3a7.5 2.5 0 0 0 7.5-2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
