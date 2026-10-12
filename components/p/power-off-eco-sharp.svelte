<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="et_xc3zja"/><path class="l1tk8rgvq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:power-off-eco-sharp" {...props}></Icon>
<style>
:global(.et_xc3zja) {
  d: path("M6.5 7.25a8 8 0 1 0 11 0M12 2.75v7.5");
}

:global(.l1tk8rgvq) {
  d: path("M9.25 17.25c.25-2.8 1.65-4 5.5-4c-.25 2.8-1.65 4-5.5 4Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
