<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t4l7c7bim"/><path class="xctejrqwn"/><path class="nqnw98byf"/><path class="olqfcgidt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hill-outline-regular" {...props}></Icon>
<style>
:global(.nqnw98byf) {
  d: path("M2 14h20");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.olqfcgidt) {
  d: path("M6 19h12");
}

:global(.t4l7c7bim) {
  d: path("M2 14a7 7 0 0 1 14 0");
}

:global(.xctejrqwn) {
  d: path("M12 14a5 5 0 0 1 10 0");
}

</style>
