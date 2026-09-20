<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="qd-4yjjst"/><path class="ef-n7kdoh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:caret-line-left-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ef-n7kdoh) {
  d: path("M195.06 40.61a8 8 0 0 0-8.72 1.73l-80 80a8 8 0 0 0 0 11.32l80 80A8 8 0 0 0 200 208V48a8 8 0 0 0-4.94-7.39M184 188.69L123.31 128L184 67.31ZM80 48v160a8 8 0 0 1-16 0V48a8 8 0 0 1 16 0");
}

:global(.qd-4yjjst) {
  d: path("M192 48v160l-80-80Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
