<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="y3658bbcq"/><circle class="xwv91sd-e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:coordinate-point-sharp" {...props}></Icon>
<style>
:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xwv91sd-e) {
  cx: 16.75px;
  cy: 7.25px;
  r: 1.75px;
}

:global(.y3658bbcq) {
  d: path("M12 2.75v18.5M2.75 12h18.5M7 10.75v2.5M10.75 17h2.5");
}

</style>
