<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="zewbvhb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:last-track-button" {...props}></Icon>
<style>
:global(.x-kz1kb7j) {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

:global(.zewbvhb7f) {
  fill: var(--svg-color--fff, #fff);
  d: path("M9 18L21 7v9.166L31 7v22l-10-9.167V29zm0 11H5V7h4z");
}

</style>
