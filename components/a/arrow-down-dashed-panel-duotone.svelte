<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ojh85yurv"/><path class="g9hlkrbzo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-dashed-panel-duotone" {...props}></Icon>
<style>
:global(.g9hlkrbzo) {
  d: path("M15.5 20L15.5 10M10 15L15.1314 20.5979C15.3296 20.8141 15.6704 20.8141 15.8686 20.5979L21 15");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ojh85yurv) {
  stroke-opacity: 0.4;
  d: path("M3 6C3 4.3431 4.3431 3 6 3M10.5 3L13.5 3M21 7L21 6.0003C21 4.3434 19.6569 3 18 3M7 21L6 21C4.3431 21 3 19.6569 3 18M3 10.5L3 13.5");
}

</style>
