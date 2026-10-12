<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tlkzz9bje"/><circle class="wijmr5spd"/><path class="yt0k09bcz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lecture-sharp" {...props}></Icon>
<style>
:global(.tlkzz9bje) {
  d: path("M6.25 11.75h13l-.23 1.48l-1.04 6.54l-.23 1.48H6.25l-.23-1.48l-1.04-6.54l-.23-1.48z");
}

:global(.wijmr5spd) {
  cx: 12px;
  cy: 5.75px;
  r: 3px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yt0k09bcz) {
  d: path("m16.75 11.75l1.5-3.5m-8 8h3.5");
}

</style>
