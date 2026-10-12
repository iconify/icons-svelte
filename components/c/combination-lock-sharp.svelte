<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bwcocbc-k"/><circle class="cm25e9ila"/><circle class="cced_l5jl"/><path class="wvuew94fb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:combination-lock-sharp" {...props}></Icon>
<style>
:global(.bwcocbc-k) {
  d: path("M7.75 9.5V7a4.25 4.25 0 0 1 8.5 0v2.5");
}

:global(.cced_l5jl) {
  cx: 12px;
  cy: 14.5px;
  r: 3px;
}

:global(.cm25e9ila) {
  cx: 12px;
  cy: 14.5px;
  r: 6.75px;
}

:global(.wvuew94fb) {
  d: path("M12 14.5V13");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
