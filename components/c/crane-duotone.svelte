<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="nnu0x1y2t"/><path class="c48-ycc6q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:crane-duotone" {...props}></Icon>
<style>
:global(.c48-ycc6q) {
  d: path("M228.12 17.14a8 8 0 0 0-7.88-.2L102 80H32a16 16 0 0 0-16 16v104a16 16 0 0 0 16 16h88a16 16 0 0 0 16-16v-32a7.8 7.8 0 0 0-.34-2.3L113.54 92L216 37.33V160h-16v-8a8 8 0 0 0-16 0v8a16 16 0 0 0 16 16h16a16 16 0 0 0 16-16V24a8 8 0 0 0-3.88-6.86M98.05 96l19.2 64H64V96ZM48 96v64H32V96ZM32 200v-24h88v24Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.nnu0x1y2t) {
  d: path("M128 168H56V88h48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
