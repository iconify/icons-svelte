<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="uja6btbrh"/><path class="mm0vbdtdx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-elbow-right-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.mm0vbdtdx) {
  d: path("M232 72h-72a8 8 0 0 0-5.66 13.66L184.69 116L120 180.69L29.66 90.34a8 8 0 0 0-11.32 11.32l96 96a8 8 0 0 0 11.32 0L196 127.31l30.34 30.35A8 8 0 0 0 240 152V80a8 8 0 0 0-8-8m-8 60.69L179.31 88H224Z");
}

:global(.uja6btbrh) {
  d: path("M232 80v72l-72-72Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
