<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n2cze8b3i"/><path class="rivtgs6sw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:excavator-duocolor-sharp" {...props}></Icon>
<style>
:global(.n2cze8b3i) {
  stroke-opacity: 0.4;
  d: path("m13 13l3-8l5 5v5h-2l-1-2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rivtgs6sw) {
  d: path("M3 18a2 2 0 0 1 2-2h8a2 2 0 1 1 0 4H5a2 2 0 0 1-2-2m3-2V8h3l4 4v4m-7-4h6");
}

</style>
