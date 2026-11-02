<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cd4xz4odh"/><path class="tm-7tqbxw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:eject-bulk" {...props}></Icon>
<style>
:global(.cd4xz4odh) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m4.456 12.41l5-8a3 3 0 0 1 5.088 0l5 8A2.999 2.999 0 0 1 17 17H7a3 3 0 0 1-2.544-4.59");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.tm-7tqbxw) {
  d: path("M5 19h14a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2");
}

</style>
