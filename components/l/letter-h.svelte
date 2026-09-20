<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="pb_p_5bbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:letter-h" {...props}></Icon>
<style>
:global(.pb_p_5bbj) {
  fill: var(--svg-color--fff, #fff);
  d: path("M25.5 7A2.5 2.5 0 0 0 23 9.5V15H13V9.5a2.5 2.5 0 1 0-5 0v17a2.5 2.5 0 1 0 5 0V20h10v6.5a2.5 2.5 0 1 0 5 0v-17A2.5 2.5 0 0 0 25.5 7");
}

:global(.x-kz1kb7j) {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
