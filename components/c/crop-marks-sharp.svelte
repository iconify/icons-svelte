<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m9vadkbmx"/><path class="pnf7szbuz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:crop-marks-sharp" {...props}></Icon>
<style>
:global(.m9vadkbmx) {
  d: path("M6.75 2.75v14.5h14.5");
}

:global(.pnf7szbuz) {
  d: path("M2.75 6.75h14.5v14.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
