<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qbn9ahbbt"/><path class="y7hhsvtxz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cinder-block-sharp" {...props}></Icon>
<style>
:global(.qbn9ahbbt) {
  d: path("M2.75 6.75h18.5v10.5H2.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y7hhsvtxz) {
  d: path("M6.75 10h3.5v4H6v-4zm7.75 0H18v4h-4.25v-4z");
}

</style>
