<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v_qg2hb2n"/><path class="j8yx7sbbx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-pull-request-draft-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.j8yx7sbbx) {
  d: path("M19 5h.01a1 1 0 0 1 0 2H19a1 1 0 0 1 0-2M4 16V8a1 1 0 0 1 2 0v8a1 1 0 0 1-2 0m15-6h.01a1 1 0 0 1 0 2H19a1 1 0 0 1 0-2");
}

:global(.v_qg2hb2n) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0m0 12a3 3 0 1 1 6 0a3 3 0 0 1-6 0m14 0a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
