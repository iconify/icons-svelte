<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="a_0vr5b0m"/><circle class="ux15onb8l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:group-objects-sharp" {...props}></Icon>
<style>
:global(.a_0vr5b0m) {
  d: path("M2.75 6.5V2.75H6.5m11 0h3.75V6.5m0 11v3.75H17.5m-11 0H2.75V17.5m3.5-11.25h5.5v5.5h-5.5z");
}

:global(.ux15onb8l) {
  cx: 15.5px;
  cy: 15.5px;
  r: 2.75px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
