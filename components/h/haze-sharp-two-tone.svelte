<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="k9swfv54z"/><path class="pi-cetb9l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:haze-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.k9swfv54z) {
  stroke-opacity: 0.4;
  d: path("M3 17H21M4 22H11M13 22H20");
}

:global(.pi-cetb9l) {
  d: path("M7.5 13V12C7.5 9.515 9.515 7.5 12 7.5C14.485 7.5 16.5 9.515 16.5 12V13M1 12H4.5M19.5 12H23M4.636 4.636L6.282 6.282M19.364 4.636L17.718 6.282M12 4.5V1");
}

</style>
