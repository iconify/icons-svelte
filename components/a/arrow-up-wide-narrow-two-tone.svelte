<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q7ot8ryau"/><path class="alpsapn4b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-up-wide-narrow-two-tone" {...props}></Icon>
<style>
:global(.alpsapn4b) {
  d: path("M6 18V6M2 10L5.6464 6.3536C5.8417 6.1583 6.1583 6.1583 6.3536 6.3536L10 10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q7ot8ryau) {
  stroke-opacity: 0.4;
  d: path("M14 6H22M14 10H20M14 14H18M14 18H16");
}

</style>
