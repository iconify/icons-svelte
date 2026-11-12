<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h1g3kmb0e"/><path class="wd-jkl99n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:radiator-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.h1g3kmb0e) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 4a2 2 0 1 1 4 0v16a2 2 0 1 1-4 0Zm7 0a2 2 0 1 1 4 0v16a2 2 0 1 1-4 0Zm7 0a2 2 0 1 1 4 0v16a2 2 0 1 1-4 0Z");
}

:global(.wd-jkl99n) {
  d: path("M3 7h16a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m2 8h16a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2");
}

</style>
