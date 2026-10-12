<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="f2hbp00fv"/><path class="m3i8hg_zf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:parking-meter-sharp" {...props}></Icon>
<style>
:global(.f2hbp00fv) {
  d: path("M6.75 2.75h10.5v10H6.75z");
}

:global(.m3i8hg_zf) {
  d: path("M9 8.5a3 3 0 0 1 6 0m-3 0L13.5 7M12 12.75v8.5m-3 0h6");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
