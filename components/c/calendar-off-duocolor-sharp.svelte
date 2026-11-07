<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jvayet_ht"/><path class="lza_srbha"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-off-duocolor-sharp" {...props}></Icon>
<style>
:global(.jvayet_ht) {
  stroke-opacity: 0.4;
  d: path("M16 3v2M2 2l20 20");
}

:global(.lza_srbha) {
  d: path("M21 21H4V4m7 1h9v9M4 9h5m6 0h5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
