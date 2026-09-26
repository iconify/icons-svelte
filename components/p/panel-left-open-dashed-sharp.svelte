<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lzd54cadi"/><path class="h5zq5sxkr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-left-open-dashed-sharp" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.h5zq5sxkr) {
  d: path("M12.7071 8.7071L16 12L12.7071 15.2929");
}

:global(.lzd54cadi) {
  d: path("M9 3L3 3L3 21L9 21L9 3ZM17 3L21 3L21 7M21 17L21 21L17 21M12 3L15 3M12 21L15 21M21 9.5L21 14.5");
}

</style>
