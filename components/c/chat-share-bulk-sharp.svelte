<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jer5s5b2c"/><path class="beaj39ecj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-share-bulk-sharp" {...props}></Icon>
<style>
:global(.beaj39ecj) {
  d: path("M16.707 9.293a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L13.586 11H9v2a1 1 0 0 1-2 0v-3a1 1 0 0 1 1-1h5.586l-1.293-1.293a.999.999 0 1 1 1.414-1.414Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.jer5s5b2c) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 18H7.414l-3.707 3.707A1 1 0 0 1 2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1");
}

</style>
