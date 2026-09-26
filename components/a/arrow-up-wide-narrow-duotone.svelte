<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ie7-rmbwb"/><path class="lbe7xcbft"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-up-wide-narrow-duotone" {...props}></Icon>
<style>
:global(.ie7-rmbwb) {
  stroke-opacity: 0.4;
  d: path("M14 6L22 6M14 10L20 10M14 14L18 14M14 18L16 18");
}

:global(.lbe7xcbft) {
  d: path("M6 18L6 6M2 10L5.6464 6.3536C5.8417 6.1583 6.1583 6.1583 6.3536 6.3536L10 10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
