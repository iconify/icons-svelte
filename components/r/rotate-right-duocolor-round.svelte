<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aztql-b4w"/><path class="lvoahibxm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:rotate-right-duocolor-round" {...props}></Icon>
<style>
:global(.aztql-b4w) {
  stroke-opacity: 0.4;
  d: path("M12 6H9a4 4 0 0 0-4 4m4-7l3 3l-3 3");
}

:global(.lvoahibxm) {
  d: path("M5 14v2a4 4 0 0 0 4 4h6a4 4 0 0 0 4-4V9a3 3 0 0 0-3-3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
