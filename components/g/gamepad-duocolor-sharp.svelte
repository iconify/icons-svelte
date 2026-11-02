<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r8h3aabwm"/><path class="r21jxhxfq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:gamepad-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r21jxhxfq) {
  d: path("M3 5h18v14H3Z");
}

:global(.r8h3aabwm) {
  stroke-opacity: 0.4;
  d: path("M7 12h6m-3-3v6m6-1h.01M18 10h.01");
}

</style>
