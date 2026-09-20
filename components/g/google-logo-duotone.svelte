<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="fw_-f4u_a"/><path class="won3kebwh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:google-logo-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.fw_-f4u_a) {
  d: path("M216 128a88 88 0 1 1-88-88a88 88 0 0 1 88 88");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.won3kebwh) {
  d: path("M224 128a96 96 0 1 1-21.95-61.09a8 8 0 1 1-12.33 10.18A80 80 0 1 0 207.6 136H128a8 8 0 0 1 0-16h88a8 8 0 0 1 8 8");
}

</style>
