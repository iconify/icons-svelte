<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n92hyrp1a"/><path class="ik93a37tn"/><path class="vjdmi0bfh"/><path class="qh-87afpi"/><path class="bo51iypxr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:blossom-outline-regular" {...props}></Icon>
<style>
:global(.bo51iypxr) {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ik93a37tn) {
  d: path("M4 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.n92hyrp1a) {
  d: path("M9 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qh-87afpi) {
  d: path("M9 17a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.vjdmi0bfh) {
  d: path("M14 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
