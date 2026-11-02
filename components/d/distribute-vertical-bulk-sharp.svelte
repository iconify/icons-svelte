<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ajm53ku0m"/><path class="x0p8qfbfb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:distribute-vertical-bulk-sharp" {...props}></Icon>
<style>
:global(.ajm53ku0m) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 15V9a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.x0p8qfbfb) {
  d: path("M3 3h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m0 16h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
