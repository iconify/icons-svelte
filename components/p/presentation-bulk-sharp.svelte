<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fx5k2nb_n"/><path class="i11ylvpcu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:presentation-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.fx5k2nb_n) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Z");
}

:global(.i11ylvpcu) {
  d: path("M21 2a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm-3.293 18.293a.999.999 0 1 1-1.414 1.414L12 17.414l-4.293 4.293a.999.999 0 1 1-1.414-1.414l5-5a1 1 0 0 1 1.414 0Z");
}

</style>
