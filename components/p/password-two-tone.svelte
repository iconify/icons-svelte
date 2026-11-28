<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n4lt2ta4p"/><path class="yer-e4b7i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:password-two-tone" {...props}></Icon>
<style>
:global(.n4lt2ta4p) {
  d: path("M4 7V12M2 11L6 8M2 8L6 11M12 7V12M10 11L14 8M10 8L14 11M20 7V12M18 11L22 8M18 8L22 11");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.yer-e4b7i) {
  stroke-opacity: 0.4;
  d: path("M2 17H22");
}

</style>
