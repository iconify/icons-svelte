<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="md2-ubbkw"/><path class="wjnwtubpm"/><path class="w3b9nxekf"/><path class="w3fj3ibba"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevrons-up-down-broken" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.md2-ubbkw) {
  d: path("M13.5 19.5L12 21L6 15");
}

:global(.w3b9nxekf) {
  d: path("M13.5 4.5L12 3L6 9");
}

:global(.w3fj3ibba) {
  d: path("M16.5 7.5L18 9");
}

:global(.wjnwtubpm) {
  d: path("M16.5 16.5L18 15");
}

</style>
