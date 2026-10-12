<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="jl4903ezj"/><path class="bc4cf30-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lollipop-sharp" {...props}></Icon>
<style>
:global(.bc4cf30-k) {
  d: path("M12.5 9.25a1.25 1.25 0 0 0-2.5 0a2.5 2.5 0 0 0 5 0m-3 6.5v5.5");
}

:global(.jl4903ezj) {
  cx: 12px;
  cy: 9.25px;
  r: 6.5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
