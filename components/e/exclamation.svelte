<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="zx2fq2bkw"/><path class="srgb_vzch"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:exclamation" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.srgb_vzch) {
  d: path("M12 16a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

:global(.zx2fq2bkw) {
  fill-rule: evenodd;
  d: path("M10 2a2 2 0 0 1 2 2v7a2 2 0 1 1-4 0V4a2 2 0 0 1 2-2");
}

</style>
