<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nrnkr7bfl"/><path class="fdr57lb7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:inverter-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.fdr57lb7d) {
  d: path("M7 11V8a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v3a1 1 0 0 1-.2.6a6 6 0 0 1-9.6 0A1 1 0 0 1 7 11m8-.354V8H9v2.646a4 4 0 0 0 6 0M9 16h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

:global(.nrnkr7bfl) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 5a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Z");
}

</style>
