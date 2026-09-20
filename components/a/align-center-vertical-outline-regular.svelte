<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rr985ibot"/><path class="c3a-odz8a"/><path class="akf7y5bsb"/><path class="xgyiae7-j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:align-center-vertical-outline-regular" {...props}></Icon>
<style>
:global(.akf7y5bsb) {
  d: path("M8 7h8v4H8Z");
}

:global(.c3a-odz8a) {
  d: path("M12 18.5V21");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rr985ibot) {
  d: path("M12 3v2.5");
}

:global(.xgyiae7-j) {
  d: path("M9.5 14h5v4h-5Z");
}

</style>
