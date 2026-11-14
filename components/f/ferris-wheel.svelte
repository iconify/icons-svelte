<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mzsqplboh"/><path class="z0k0x6_ag"/><path class="v4gve_jid"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ferris-wheel" {...props}></Icon>
<style>
:global(.mzsqplboh) {
  d: path("M5 10a7 7 0 1 0 14 0a7 7 0 1 0-14 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v4gve_jid) {
  d: path("m8 21l4-11l4 11");
}

:global(.z0k0x6_ag) {
  d: path("M10.75 10a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0ZM12 3v14m-7-7h14M7 5l10 10m0-10L7 15");
}

</style>
