<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="di23f0b_l"/><path class="sdusgzyyf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hand-grab-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.di23f0b_l) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 6a3 3 0 0 1 3 3v6a7 7 0 0 1-7 7h-4a7 7 0 0 1-7-7v-3a3 3 0 0 1 4-2.829V9a3 3 0 0 1 4.471-2.615a3 3 0 0 1 5.058 0A3 3 0 0 1 17.997 6Z");
}

:global(.sdusgzyyf) {
  d: path("M13 12a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0Zm-8 3a1 1 0 0 1-2 0v-3a1 1 0 0 1 2 0Z");
}

</style>
