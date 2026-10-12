<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="utc29-bcy"/><path class="l2_9_1byq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:breakpoint-sharp" {...props}></Icon>
<style>
:global(.l2_9_1byq) {
  d: path("M13.25 6.75h7m-7 5.25h7m-7 5.25h4.5");
}

:global(.utc29-bcy) {
  cx: 7px;
  cy: 12px;
  r: 3.25px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
