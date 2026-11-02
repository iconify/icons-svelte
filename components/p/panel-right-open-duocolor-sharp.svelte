<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lngqv7bke"/><path class="fx3dyzbmz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:panel-right-open-duocolor-sharp" {...props}></Icon>
<style>
:global(.fx3dyzbmz) {
  d: path("M4 4h16v16H4Zm11 0v16");
}

:global(.lngqv7bke) {
  stroke-opacity: 0.4;
  d: path("m11 9l-3 3l3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
