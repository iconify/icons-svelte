<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a9g3-t9mx"/><path class="bs657w5zt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-up-two-tone" {...props}></Icon>
<style>
:global(.a9g3-t9mx) {
  stroke-opacity: 0.4;
  d: path("M17 21L17 3M13 7L17 3L21 7");
}

:global(.bs657w5zt) {
  d: path("M7 3L7 21M11 17L7 21L3 17");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
