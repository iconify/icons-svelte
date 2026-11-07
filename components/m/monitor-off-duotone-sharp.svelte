<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w3gqynb9v"/><path class="kbxa8ccbj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:monitor-off-duotone-sharp" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.kbxa8ccbj) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 17H4V3m7 1h9v9M9 20h6M3 2l19 19");
}

:global(.w3gqynb9v) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 17H4V4h1ZM11 4h9v9Z");
}

</style>
