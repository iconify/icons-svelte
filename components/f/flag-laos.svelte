<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="o5utzu05n"/><path class="hjb8r88sk"/><circle class="ehgj8rbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-laos" {...props}></Icon>
<style>
:global(.ehgj8rbhj) {
  cx: 18px;
  cy: 18px;
  r: 5px;
  fill: var(--svg-color--fff, #fff);
}

:global(.hjb8r88sk) {
  fill: var(--svg-color--002868, #002868);
  d: path("M0 24h36V12H0zm18-11a5 5 0 1 1-.001 10.001A5 5 0 0 1 18 13");
}

:global(.o5utzu05n) {
  fill: var(--svg-color--ce1126, #ce1126);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-3H0zM32 5H4a4 4 0 0 0-4 4v3h36V9a4 4 0 0 0-4-4");
}

</style>
