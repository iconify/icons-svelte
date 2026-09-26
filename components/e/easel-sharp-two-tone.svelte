<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="b3o7g4byv"/><path class="fpzfo4b8o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:easel-sharp-two-tone" {...props}></Icon>
<style>
:global(.b3o7g4byv) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 2L20 2C20.5523 2 21 2.4477 21 3L21 16C21 16.5523 20.5523 17 20 17L4 17C3.4477 17 3 16.5523 3 16L3 3C3 2.4477 3.4477 2 4 2Z");
  stroke: none;
}

:global(.fpzfo4b8o) {
  d: path("M4 3L20 3L20 16L4 16L4 3ZM1 16L23 16M8 16L6.2862 21.7127M16 16L17.7138 21.7127M12 16L12 20");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
