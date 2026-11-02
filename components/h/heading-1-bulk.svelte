<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f42qt1j4y"/><path class="y4tx-xbdi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:heading-1-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.f42qt1j4y) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.293 8.293A1 1 0 0 1 20 9v10a1 1 0 0 1-2 0v-7.586l-.293.293a.999.999 0 1 1-1.414-1.414Z");
}

:global(.y4tx-xbdi) {
  d: path("M4 11h6V5a1 1 0 0 1 2 0v14a1 1 0 0 1-2 0v-6H4v6a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Z");
}

</style>
