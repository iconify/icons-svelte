<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wpqcgi2_k"/><path class="xotxp7bir"/><path class="vlspyzbym"/><path class="tl5daebtp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:biodiversity-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tl5daebtp) {
  d: path("M13 16a5 5 0 0 1 9 0 4 4 0 0 1 -4.5 4 4 4 0 0 1 -4.5 -4");
}

:global(.vlspyzbym) {
  d: path("M17 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.wpqcgi2_k) {
  d: path("M10 5c0 6 -3 9 -8 9 0 -6 3 -9 8 -9");
}

:global(.xotxp7bir) {
  d: path("M12 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
