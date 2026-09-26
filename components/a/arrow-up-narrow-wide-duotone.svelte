<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vpj4m7rea"/><path class="lbe7xcbft"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-up-narrow-wide-duotone" {...props}></Icon>
<style>
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

:global(.vpj4m7rea) {
  stroke-opacity: 0.4;
  d: path("M14 10L18 10M14 14L20 14M14 18L22 18M14 6L16 6");
}

</style>
