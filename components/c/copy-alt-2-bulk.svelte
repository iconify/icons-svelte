<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v9nak9bvl"/><path class="arh_g9bto"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:copy-alt-2-bulk" {...props}></Icon>
<style>
:global(.arh_g9bto) {
  d: path("M11 2h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3a1 1 0 0 1 0-2a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1h-8a.997.997 0 0 0-1 1a1 1 0 0 1-2 0a3 3 0 0 1 3-3");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.v9nak9bvl) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 11a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
