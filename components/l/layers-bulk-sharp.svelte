<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ba9qrbb8a"/><path class="vs-8b8bpm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:layers-bulk-sharp" {...props}></Icon>
<style>
:global(.ba9qrbb8a) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m7.553 5.106l4-2a1 1 0 0 1 .894 0l8 4a.998.998 0 0 1 0 1.788l-8 4a1 1 0 0 1-.894 0l-8-4a.998.998 0 0 1 0-1.788Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.vs-8b8bpm) {
  d: path("M4.447 11.106L12 14.882l7.553-3.776a1 1 0 1 1 .894 1.788l-8 4a1 1 0 0 1-.894 0l-8-4a1 1 0 1 1 .894-1.788m0 4L12 18.882l7.553-3.776a1 1 0 1 1 .894 1.788l-8 4a1 1 0 0 1-.894 0l-8-4a1 1 0 1 1 .894-1.788");
}

</style>
