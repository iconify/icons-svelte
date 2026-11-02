<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i0kbhhn6z"/><path class="kwh_pwbjw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-help-duocolor-sharp" {...props}></Icon>
<style>
:global(.i0kbhhn6z) {
  stroke-opacity: 0.4;
  d: path("M10 9a2 2 0 1 1 2 2m0 3h.01");
}

:global(.kwh_pwbjw) {
  d: path("M12 17H7l-4 4V3h18v14z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
