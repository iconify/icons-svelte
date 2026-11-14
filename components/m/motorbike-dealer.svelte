<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ke58ybbzd"/><path class="xsq4lbb-v"/><path class="y_uza4brl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:motorbike-dealer" {...props}></Icon>
<style>
:global(.ke58ybbzd) {
  d: path("M3.5 10.5L12 3.25l8.5 7.25v10h-17Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xsq4lbb-v) {
  d: path("M6.5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.y_uza4brl) {
  d: path("m8.5 18.5l2.5-4h3.5l1 4m-1-4l-.5-2h1.5");
}

</style>
