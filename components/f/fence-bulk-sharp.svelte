<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l__s29bso"/><path class="ohs7azhmj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fence-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.l__s29bso) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 7c0-.155.036-.308.106-.447l2-4a.998.998 0 0 1 1.788 0l2 4c.07.139.106.292.106.447v14a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1ZM4 7c0-.155.036-.308.106-.447l2-4a.998.998 0 0 1 1.788 0l2 4c.07.139.106.292.106.447v14a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Z");
}

:global(.ohs7azhmj) {
  d: path("M3 9h2a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m6 0h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m10 0h2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2M3 15h2a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m6 0h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m10 0h2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2");
}

</style>
