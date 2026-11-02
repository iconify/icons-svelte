<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nau3f9luo"/><path class="r1ciqdbuo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:briefcase-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.nau3f9luo) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 7h18a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1");
}

:global(.r1ciqdbuo) {
  d: path("M7.393 6.053A5 5 0 0 1 17 8a1 1 0 0 1-2 0a2.998 2.998 0 0 0-4.962-2.269A3 3 0 0 0 9 8a1 1 0 0 1-2 0a5 5 0 0 1 .393-1.947");
}

</style>
