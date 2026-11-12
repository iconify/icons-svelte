<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e2mhiz0sy"/><path class="f40jmzbqv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:markdown-duocolor-sharp" {...props}></Icon>
<style>
:global(.e2mhiz0sy) {
  stroke-opacity: 0.4;
  d: path("M18 7v10m-3-3l3 3l3-3");
}

:global(.f40jmzbqv) {
  d: path("M3 17V7l4 5l4-5v10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
