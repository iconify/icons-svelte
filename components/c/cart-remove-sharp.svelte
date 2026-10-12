<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="g0xnjl1rh"/><circle class="fpq61538s"/><circle class="vzw8i56kn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cart-remove-sharp" {...props}></Icon>
<style>
:global(.fpq61538s) {
  cx: 9.25px;
  cy: 18.75px;
  r: 1.5px;
}

:global(.g0xnjl1rh) {
  d: path("M2.75 3.75h1.4l1.184-.001L5.61 4.9L7.65 14m-1.7-7.75H19.5l1.276.001l-.306 1.239l-1.2 4.8l-.245 1.677L17.33 14H7.65Z");
}

:global(.vzw8i56kn) {
  cx: 17.25px;
  cy: 18.75px;
  r: 1.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
