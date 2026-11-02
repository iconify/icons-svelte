<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x71w8dboq"/><path class="zae_u_brw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-left-to-line-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.x71w8dboq) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 6v12a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0");
}

:global(.zae_u_brw) {
  d: path("M10.414 11H20a1 1 0 0 1 0 2h-9.586l2.293 2.293a.999.999 0 1 1-1.414 1.414l-4-4a.997.997 0 0 1 0-1.414l4-4a.999.999 0 1 1 1.414 1.414Z");
}

</style>
