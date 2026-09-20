<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="h9cp27m5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:fast-down-button" {...props}></Icon>
<style>
:global(.h9cp27m5c) {
  fill: var(--svg-color--fff, #fff);
  d: path("m18 30l11-12h-9.166L29 8H7l9.167 10H7z");
}

:global(.x-kz1kb7j) {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
