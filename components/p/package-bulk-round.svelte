<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vrqov37jv"/><path class="s95zvrsyk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:package-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.s95zvrsyk) {
  d: path("M4 7h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2");
}

:global(.vrqov37jv) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 8c0-.155.036-.308.106-.447l1-2C4.848 4.069 6.307 3 8 3h8c1.693 0 3.152 1.069 3.894 2.553l1 2c.07.139.106.292.106.447v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 21H8a5 5 0 0 1-5-5Z");
}

</style>
