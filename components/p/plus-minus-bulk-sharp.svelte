<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a06aaqtap"/><path class="juiz4l5bu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:plus-minus-bulk-sharp" {...props}></Icon>
<style>
:global(.a06aaqtap) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 19h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.juiz4l5bu) {
  d: path("M13 9h5a1 1 0 0 1 0 2h-5v5a1 1 0 0 1-2 0v-5H6a1 1 0 0 1 0-2h5V4a1 1 0 0 1 2 0Z");
}

</style>
