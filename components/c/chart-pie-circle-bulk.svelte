<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="no3egd27f"/><path class="ffm8-pbcs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-pie-circle-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ffm8-pbcs) {
  d: path("M14 18a4 4 0 1 1 8 0a4 4 0 0 1-8 0m3.222 1.843a2.001 2.001 0 0 0 1.556-3.686a2 2 0 0 0-1.556 3.686");
}

:global(.no3egd27f) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 13h-8v8a1 1 0 0 1-1 1a10 10 0 1 1 10-10a1 1 0 0 1-1 1");
}

</style>
