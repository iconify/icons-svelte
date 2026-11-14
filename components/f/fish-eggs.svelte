<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cct_g31hh"/><path class="uhy-iqbkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fish-eggs" {...props}></Icon>
<style>
:global(.cct_g31hh) {
  d: path("M6 9.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm6 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.uhy-iqbkv) {
  d: path("M3 14.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm6 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm6 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
