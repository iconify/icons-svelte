<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bwe_218us"/><path class="rgnjs8brm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:panel-left-bulk-round" {...props}></Icon>
<style>
:global(.bwe_218us) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 3a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 21H8a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.rgnjs8brm) {
  d: path("M10 4v16a1 1 0 0 1-2 0V4a1 1 0 0 1 2 0");
}

</style>
