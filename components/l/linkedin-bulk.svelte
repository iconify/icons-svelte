<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qebz58hxe"/><path class="fkmfswd3c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:linkedin-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.fkmfswd3c) {
  d: path("M8.01 7a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2ZM9 16a1 1 0 0 1-2 0v-5a1 1 0 0 1 2 0Zm2-3a3 3 0 1 1 6 0v3a1 1 0 0 1-2 0v-3a1 1 0 0 0-2 0v3a1 1 0 0 1-2 0Z");
}

:global(.qebz58hxe) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
