<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="ayv26ub5y"/><path class="h38a4ib1g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:bookmarks-simple-fill" {...props}></Icon>
<style>
:global(.ayv26ub5y) {
  d: path("M160 56H64a16 16 0 0 0-16 16v152a8 8 0 0 0 12.65 6.51L112 193.83l51.36 36.68A8 8 0 0 0 176 224V72a16 16 0 0 0-16-16");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.h38a4ib1g) {
  d: path("M192 24H88a8 8 0 0 0 0 16h104v152a8 8 0 0 0 16 0V40a16 16 0 0 0-16-16");
}

</style>
