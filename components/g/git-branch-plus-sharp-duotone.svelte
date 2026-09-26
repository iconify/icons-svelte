<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dmkuafbjo"/><path class="zimbowb2d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-branch-plus-sharp-duotone" {...props}></Icon>
<style>
:global(.dmkuafbjo) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 2C8.0711 2 10 3.9289 10 6C10 8.0711 8.0711 10 6 10C3.9289 10 2 8.0711 2 6C2 3.9289 3.9289 2 6 2ZM18 14C20.0711 14 22 15.9289 22 18C22 20.0711 20.0711 22 18 22C15.9289 22 14 20.0711 14 18C14 15.9289 15.9289 14 18 14Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zimbowb2d) {
  d: path("M6 22L6 9C6.1667 12 8.2 18 15 18M18 10L18 2M14 6L22 6");
}

</style>
