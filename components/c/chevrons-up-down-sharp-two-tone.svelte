<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="gdbpwrebz"/><path class="hlolnvb6o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chevrons-up-down-sharp-two-tone" {...props}></Icon>
<style>
:global(.gdbpwrebz) {
  stroke-opacity: 0.4;
  d: path("M6.7071 9.2929L12 4L17.2929 9.2929");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.hlolnvb6o) {
  d: path("M6.7071 14.7071L12 20L17.2929 14.7071");
}

</style>
