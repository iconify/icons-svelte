<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="t5sz53b0n"/><path class="hzp_xcbkd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:folder-lock-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.hzp_xcbkd) {
  d: path("M224 160h-8v-4a28 28 0 0 0-56 0v4h-8a8 8 0 0 0-8 8v40a8 8 0 0 0 8 8h72a8 8 0 0 0 8-8v-40a8 8 0 0 0-8-8m-48-4a12 12 0 0 1 24 0v4h-24Zm40 44h-56v-24h56Zm0-128h-84.69L104 44.69A15.86 15.86 0 0 0 92.69 40H40a16 16 0 0 0-16 16v144.62A15.4 15.4 0 0 0 39.38 216h73.18a8 8 0 0 0 0-16H40V88h176v16a8 8 0 0 0 16 0V88a16 16 0 0 0-16-16M92.69 56l16 16H40V56Z");
}

:global(.t5sz53b0n) {
  d: path("M224 168v40h-72v-40ZM92.69 48H40a8 8 0 0 0-8 8v24h96L98.34 50.34A8 8 0 0 0 92.69 48");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
