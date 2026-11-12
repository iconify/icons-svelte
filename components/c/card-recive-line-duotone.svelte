<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="g56u1es1x"/><path class="tu2r7ibad"/><path class="bbqlgybvp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:card-recive-line-duotone" {...props}></Icon>
<style>
:global(.bbqlgybvp) {
  d: path("M10 16H6m7 0h-.5M2 10h20");
  opacity: var(--svg-opacity--0-4, 0.4);
}

:global(.g56u1es1x) {
  stroke-linejoin: round;
  d: path("M19 14v6m0 0l2-2m-2 2l-2-2");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tu2r7ibad) {
  d: path("M22 12c0-3.771 0-5.657-1.172-6.828S17.771 4 14 4h-4C6.229 4 4.343 4 3.172 5.172S2 8.229 2 12s0 5.657 1.172 6.828S6.229 20 10 20h4");
}

</style>
