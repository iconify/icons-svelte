<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fa_nbjbrc"/><path class="qnvxqebrk"/><path class="u__znebfc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pedestrian-detour" {...props}></Icon>
<style>
:global(.fa_nbjbrc) {
  d: path("M12 2.25L21.75 12L12 21.75L2.25 12Zm-1.5 14v-8.5");
}

:global(.qnvxqebrk) {
  d: path("M10.5 14q0-4 4-4h.75");
}

:global(.u__znebfc) {
  d: path("m13.25 8l2 2l-2 2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
