<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="omg2s3ocq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:eject-button" {...props}></Icon>
<style>
:global(.omg2s3ocq) {
  fill: var(--svg-color--fff, #fff);
  d: path("M6 29v-5h24v5zM18 6L6 20h24z");
}

:global(.x-kz1kb7j) {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
