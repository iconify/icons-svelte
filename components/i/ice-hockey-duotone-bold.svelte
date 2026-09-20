<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="quuk74b3k"/><path class="rmcfrrb-t"/><path class="oiqkce4vb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ice-hockey-duotone-bold" {...props}></Icon>
<style>
:global(.oiqkce4vb) {
  d: path("M13 5h6v4h-6Z");
}

:global(.quuk74b3k) {
  fill: currentColor;
  d: path("M13 5h6v4h-6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rmcfrrb-t) {
  d: path("M6 3v12c0 3 2 4 5 4h6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
