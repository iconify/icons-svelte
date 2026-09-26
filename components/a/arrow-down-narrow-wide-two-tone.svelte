<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="efcdqybup"/><path class="oeb9303bc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-narrow-wide-two-tone" {...props}></Icon>
<style>
:global(.efcdqybup) {
  stroke-opacity: 0.4;
  d: path("M14 6H16M14 10H18M14 14H20M14 18H22");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oeb9303bc) {
  d: path("M6 6V18M2 14L5.6464 17.6464C5.8417 17.8417 6.1583 17.8417 6.3536 17.6464L10 14");
}

</style>
