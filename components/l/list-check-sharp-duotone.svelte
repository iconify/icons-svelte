<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lke-2pb6e"/><path class="thmoi3b9h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-check-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.lke-2pb6e) {
  stroke-opacity: 0.4;
  d: path("M1 4L23 4M1 11L23 11");
}

:global(.thmoi3b9h) {
  d: path("M1 18L7 18M9 18L15 18M17.7071 17.7071L20 20L22.1056 15.7889");
}

</style>
