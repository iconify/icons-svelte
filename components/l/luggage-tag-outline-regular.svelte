<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="naudy1b1k"/><path class="x67_elb1a"/><path class="ef5tcc6_c"/><path class="me6k632rv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:luggage-tag-outline-regular" {...props}></Icon>
<style>
:global(.ef5tcc6_c) {
  d: path("M4 16h14");
}

:global(.me6k632rv) {
  d: path("M4 20h10");
}

:global(.naudy1b1k) {
  d: path("M6 4h10l4 4 -4 4H6Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.x67_elb1a) {
  d: path("M8 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
