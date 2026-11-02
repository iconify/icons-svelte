<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nt9a1bc7y"/><path class="d94ml7bdn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:battery-full-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.d94ml7bdn) {
  d: path("M7 14a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Zm3-4v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0m3 4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Zm3-4v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0m6 4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Z");
}

:global(.nt9a1bc7y) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 9a3 3 0 0 1 3-3h11a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
