<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nvb4_rb6q"/><path class="p0-yv_beu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:audio-lines-mid-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nvb4_rb6q) {
  stroke-opacity: 0.4;
  d: path("M8 7V17M16 9V15");
}

:global(.p0-yv_beu) {
  d: path("M4 9.5V14.5M12 4V20M20 9.5V14.5");
}

</style>
