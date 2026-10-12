<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pjpxcsbxg"/><circle class="gp0egaclj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:eye-sharp" {...props}></Icon>
<style>
:global(.gp0egaclj) {
  cx: 12px;
  cy: 12px;
  r: 3px;
}

:global(.pjpxcsbxg) {
  d: path("M2.75 12c1.9-4.1 5.3-6.75 9.25-6.75S19.35 7.9 21.25 12c-1.9 4.1-5.3 6.75-9.25 6.75S4.65 16.1 2.75 12Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
