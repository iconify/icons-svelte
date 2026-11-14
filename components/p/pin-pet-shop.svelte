<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bkhrxdbjt"/><path class="dj42frbcl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pin-pet-shop" {...props}></Icon>
<style>
:global(.bkhrxdbjt) {
  d: path("m3 6.5l1.25-3h15.5l1.25 3Zm1.5 0v14h15v-14");
}

:global(.dj42frbcl) {
  d: path("M9.25 16.25a2.75 2 0 1 0 5.5 0a2.75 2 0 1 0-5.5 0Zm-2.5-3.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm4-1.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm4 1.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
