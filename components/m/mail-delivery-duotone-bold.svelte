<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bzuzjlbvu"/><path class="i5oa6epzy"/><path class="yqiq35tbk"/><path class="o8od38cnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mail-delivery-duotone-bold" {...props}></Icon>
<style>
:global(.bzuzjlbvu) {
  fill: currentColor;
  d: path("M6 3v8h12V3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.i5oa6epzy) {
  d: path("M6 3v8h12V3Z");
}

:global(.o8od38cnm) {
  d: path("M4 18h16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.yqiq35tbk) {
  d: path("m6 3 5 5 5 -5");
}

</style>
