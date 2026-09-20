<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l2wdis8zs"/><path class="o77mms0ex"/><path class="vr9ht74fa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pharmacy-duotone-regular" {...props}></Icon>
<style>
:global(.l2wdis8zs) {
  fill: currentColor;
  d: path("M3 11h18a9 9 0 0 1 -18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o77mms0ex) {
  d: path("M3 11h18a9 9 0 0 1 -18 0");
}

:global(.vr9ht74fa) {
  d: path("m8 3 7 7");
}

</style>
