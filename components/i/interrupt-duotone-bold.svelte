<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sxj4u95zw"/><path class="ef5ubjb0b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:interrupt-duotone-bold" {...props}></Icon>
<style>
:global(.ef5ubjb0b) {
  d: path("M18 2 8 12h5l-8 8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sxj4u95zw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 2 8 12h5l-8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
