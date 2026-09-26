<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lke-2pb6e"/><path class="dykxq6bkf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-x-sharp-duotone" {...props}></Icon>
<style>
:global(.dykxq6bkf) {
  d: path("M1 18L7 18M9 18L15 18M17.7071 15.7071L22.2929 20.2929M22.2929 15.7071L17.7071 20.2929");
}

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

</style>
