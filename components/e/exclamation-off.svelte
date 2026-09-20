<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="zx2fq2bkw"/><path class="vu8ic4blg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:exclamation-off" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.vu8ic4blg) {
  d: path("M12 16a2 2 0 1 1-4 0a2 2 0 0 1 4 0M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

:global(.zx2fq2bkw) {
  fill-rule: evenodd;
  d: path("M10 2a2 2 0 0 1 2 2v7a2 2 0 1 1-4 0V4a2 2 0 0 1 2-2");
}

</style>
