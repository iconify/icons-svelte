<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dhpxnuokf"/><path class="te70kqbht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-line-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.dhpxnuokf) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 19h17a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1V4a1 1 0 0 1 2 0Z");
}

:global(.te70kqbht) {
  d: path("M7.293 10.293a1 1 0 0 1 1.414 0L12 13.586l8.293-8.293a.999.999 0 1 1 1.414 1.414l-9 9a1 1 0 0 1-1.414 0L8 12.414l-4.293 4.293a.999.999 0 1 1-1.414-1.414Z");
}

</style>
