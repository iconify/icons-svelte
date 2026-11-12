<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lkl0-zwpl"/><path class="kubyxu_qt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:brackets-dots-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.kubyxu_qt) {
  d: path("M4 4v16h2a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h3a1 1 0 0 1 0 2Zm17-2a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1h-3a1 1 0 0 1 0-2h2V4h-2a1 1 0 0 1 0-2Z");
}

:global(.lkl0-zwpl) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.01 5a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2Zm-6 6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2Zm-6 6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Zm6 0a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2Z");
}

</style>
