<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gapi2ab1b"/><path class="bs1hayv1w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pencil-minus-bulk-sharp" {...props}></Icon>
<style>
:global(.bs1hayv1w) {
  d: path("M4 6h6a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m10.707 2.293l3 3a.999.999 0 1 1-1.414 1.414l-3-3a.999.999 0 1 1 1.414-1.414");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.gapi2ab1b) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 17c0-.265.105-.52.293-.707l10-10a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-10 10A1 1 0 0 1 9 21H6a1 1 0 0 1-1-1Z");
}

</style>
