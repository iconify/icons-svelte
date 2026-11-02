<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lp-9_abfj"/><path class="eczipabfd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:align-bottom-duocolor-sharp" {...props}></Icon>
<style>
:global(.eczipabfd) {
  d: path("M4 4v12h6V4Zm10 4v8h6V8Z");
}

:global(.lp-9_abfj) {
  stroke-opacity: 0.4;
  d: path("M3 20h18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
