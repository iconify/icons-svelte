<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zxxvfabdr"/><path class="i-0o5ib_e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:archive-restore-duotone-sharp" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.i-0o5ib_e) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4h18v4H3Zm2 4v12h14V8m-4 6l-3-3l-3 3m3-3v6");
}

:global(.zxxvfabdr) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 8V4a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1");
}

</style>
