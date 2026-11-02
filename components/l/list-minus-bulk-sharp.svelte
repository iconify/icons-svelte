<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="euw4ylplj"/><path class="u-2brwj7e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-minus-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.euw4ylplj) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 14h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2");
}

:global(.u-2brwj7e) {
  d: path("M14 5a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm-4 5a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
