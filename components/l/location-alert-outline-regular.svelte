<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lo7kp72nh"/><path class="nimfanbbl"/><path class="lo0rkwbmg"/><path class="p4jzd4blg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:location-alert-outline-regular" {...props}></Icon>
<style>
:global(.lo0rkwbmg) {
  d: path("M18 6v7");
}

:global(.lo7kp72nh) {
  d: path("M3 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.nimfanbbl) {
  d: path("M6 11v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p4jzd4blg) {
  d: path("M17 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
