<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xbfr8jbdo"/><path class="rt42k1imi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:panel-top-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.rt42k1imi) {
  d: path("M4 8h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2");
}

:global(.xbfr8jbdo) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 18a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3Z");
}

</style>
