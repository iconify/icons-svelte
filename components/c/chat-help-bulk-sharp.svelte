<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jer5s5b2c"/><path class="c-nmx2_sh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-help-bulk-sharp" {...props}></Icon>
<style>
:global(.c-nmx2_sh) {
  d: path("M9.236 7.832A3 3 0 1 1 12 12a1 1 0 0 1 0-2a1.001 1.001 0 0 0 .707-1.707a1 1 0 0 0-1.094-.215A.99.99 0 0 0 11 9a1 1 0 0 1-2 0a3 3 0 0 1 .236-1.168M12.01 13a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.jer5s5b2c) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 18H7.414l-3.707 3.707A1 1 0 0 1 2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1");
}

</style>
