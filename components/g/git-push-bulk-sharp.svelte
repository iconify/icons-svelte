<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="iu39j_bzz"/><path class="zore3sagz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-push-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.iu39j_bzz) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 18a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

:global(.zore3sagz) {
  d: path("m8.293 5.293l2.999-3a1 1 0 0 1 1.415 0l3 3a.999.999 0 1 1-1.414 1.414L13 5.414V16a1 1 0 0 1-2 0V5.414L9.707 6.707a.999.999 0 1 1-1.414-1.414");
}

</style>
