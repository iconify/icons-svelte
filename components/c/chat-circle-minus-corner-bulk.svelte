<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bkwnc4bwk"/><path class="pk5s7xkzd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-circle-minus-corner-bulk" {...props}></Icon>
<style>
:global(.bkwnc4bwk) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 9H10a.997.997 0 0 0-1 1v10a1 1 0 0 1-.804.981l-5 1a1 1 0 0 1-1.177-1.177l.935-4.673a9.943 9.943 0 0 1 17.94-8.578A1 1 0 0 1 20 9");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.pk5s7xkzd) {
  d: path("M13 15h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2");
}

</style>
