<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qu5lrmbhn"/><path class="rt42k1imi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:panel-top-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.qu5lrmbhn) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 16a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 21H8a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5Z");
}

:global(.rt42k1imi) {
  d: path("M4 8h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2");
}

</style>
