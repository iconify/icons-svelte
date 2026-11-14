<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x564sptlv"/><path class="fuk-54b1c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:auto-tag" {...props}></Icon>
<style>
:global(.fuk-54b1c) {
  d: path("M13 10c.1 2 .9 2.9 3 3c-2.1.1-2.9 1-3 3c-.1-2-.9-2.9-3-3c2.1-.1 2.9-1 3-3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x564sptlv) {
  d: path("M3.5 3.5H12l8.5 8.5l-8.5 8.5L3.5 12ZM8 8h.01");
}

</style>
