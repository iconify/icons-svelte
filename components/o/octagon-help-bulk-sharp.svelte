<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ve6x22b9c"/><path class="ybi_gbb0b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:octagon-help-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ve6x22b9c) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 2h8c.265 0 .52.105.707.293l5 5A1 1 0 0 1 22 8v8c0 .265-.105.52-.293.707l-5 5A1 1 0 0 1 16 22H8a1 1 0 0 1-.707-.293l-5-5A1 1 0 0 1 2 16V8c0-.265.105-.52.293-.707l5-5A1 1 0 0 1 8 2");
}

:global(.ybi_gbb0b) {
  d: path("M8 11a4 4 0 1 1 4 4a1 1 0 0 1 0-2a2 2 0 1 0-2-2a1 1 0 0 1-2 0m4 5h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
