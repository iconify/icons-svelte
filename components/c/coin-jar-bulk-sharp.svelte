<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mupx_wbjm"/><path class="qka7dtbeg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:coin-jar-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.mupx_wbjm) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 5a3 3 0 1 1 6 0a3 3 0 0 1-6 0m7 2a3 3 0 1 1 6 0a3 3 0 0 1-6 0m4 4a1 1 0 0 1 1 1v1.586l1.707 1.707A1 1 0 0 1 19 16v5a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-5c0-.265.105-.52.293-.707L7 13.586V12a1 1 0 0 1 1-1Z");
}

:global(.qka7dtbeg) {
  d: path("M5.236 3.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m7 2a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338M17 11a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Z");
}

</style>
