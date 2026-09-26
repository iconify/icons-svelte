<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uzg8zabul"/><path class="wii6phqnr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-in-down-left-dashed-panel-duotone" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uzg8zabul) {
  stroke-opacity: 0.4;
  d: path("M10.5 21L13.5 21M3 13.5L3 10.5M7 3L6 3C4.3431 3 3 4.3431 3 6M3 18C3 19.6569 4.3431 21 6 21M21 17L21 18C21 19.6569 19.6569 21 18 21");
}

:global(.wii6phqnr) {
  d: path("M11.5 3L11.5 12C11.5 12.2761 11.7239 12.5 12 12.5L21 12.5M12 12L21 3");
}

</style>
