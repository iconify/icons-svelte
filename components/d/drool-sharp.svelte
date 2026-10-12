<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="l8k0glroj"/><path class="hsivu1bfy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:drool-sharp" {...props}></Icon>
<style>
:global(.dbgvcxwad) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

:global(.hsivu1bfy) {
  d: path("m14 14.5l1.25 1.833V17a1.25 1.25 0 0 1-2.5 0v-.667z");
}

:global(.l8k0glroj) {
  d: path("M7.75 10L9 8.438L10.25 10m3.5 0L15 8.438L16.25 10M8.5 14.25l2.782 1.828l3.468-1.328");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
