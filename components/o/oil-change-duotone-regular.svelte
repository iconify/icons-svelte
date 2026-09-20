<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s7tma7b6z"/><path class="x8a73k51x"/><path class="qik8460ao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:oil-change-duotone-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qik8460ao) {
  d: path("M5 21h14");
}

:global(.s7tma7b6z) {
  fill: currentColor;
  d: path("M12 2.5 16.5 7a6.5 6.5 0 1 1 -9 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.x8a73k51x) {
  d: path("M12 2.5 16.5 7a6.5 6.5 0 1 1 -9 0Z");
}

</style>
