<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="vayb2_u8x"/><path class="qnnweabny"/><circle class="diqg4cbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flower-playing-cards" {...props}></Icon>
<style>
:global(.diqg4cbnl) {
  cx: 15.276px;
  cy: 12.495px;
  r: 7.578px;
  fill: var(--svg-color--fff, #fff);
}

:global(.qnnweabny) {
  d: path("M8 36h20a4 4 0 0 0 4-4v-4c-4.117-2.744-21.139-8.233-28 0v4a4 4 0 0 0 4 4");
}

:global(.vayb2_u8x) {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M32 28H4V4a4 4 0 0 1 4-4h20a4 4 0 0 1 4 4z");
}

</style>
