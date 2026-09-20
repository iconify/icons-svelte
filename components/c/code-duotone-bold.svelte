<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pi5ondbao"/><path class="ybsd2cc6s"/><path class="onei9bb8c"/><path class="faeydrb7z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:code-duotone-bold" {...props}></Icon>
<style>
:global(.faeydrb7z) {
  d: path("m15 6 6 6 -6 6");
}

:global(.onei9bb8c) {
  d: path("m9 6 -6 6 6 6");
}

:global(.pi5ondbao) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 6 -6 6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ybsd2cc6s) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 6 6 6 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
