<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="okjsc7yvd"/><path class="eriwvwsyp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-close-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.eriwvwsyp) {
  d: path("m12 8.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L13.414 10l1.293 1.293a.999.999 0 1 1-1.414 1.414L12 11.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L10.586 10L9.293 8.707a.999.999 0 1 1 1.414-1.414Z");
}

:global(.okjsc7yvd) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 18H8c-.468 0-.98.395-1.293.707l-2 2a1.36 1.36 0 0 1-1.186.382C2.572 20.928 2 19.898 2 19V5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3");
}

</style>
