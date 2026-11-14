<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vqiv2g57z"/><path class="tib5xybap"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:package-private" {...props}></Icon>
<style>
:global(.tib5xybap) {
  d: path("m2.5 6.5l8 4l8-4m-8 4v9m4-4h7v6h-7Zm1.75 0V14a2.25 2.25 0 0 1 4.5 0v1.5m-2.75 3h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vqiv2g57z) {
  d: path("M11.742 18.879L10.5 19.5l-8-4v-9l8-4l8 4v2.456");
}

</style>
