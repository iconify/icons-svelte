<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u4ixodbit"/><path class="p3gwist-g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cup-with-straw" {...props}></Icon>
<style>
:global(.p3gwist-g) {
  d: path("M12 7V4l3-1.5");
}

:global(.u4ixodbit) {
  d: path("m7 11l1.5 10.5h7L17 11M6 11a6 4 0 0 1 12 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
