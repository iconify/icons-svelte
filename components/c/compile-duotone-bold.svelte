<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zu8e5tltb"/><path class="k00r0bcel"/><path class="ex--p3bfo"/><path class="p1-4htbpj"/><path class="e5d_yrbyo"/><path class="l5r0hwbum"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:compile-duotone-bold" {...props}></Icon>
<style>
:global(.e5d_yrbyo) {
  d: path("M12 13h9");
}

:global(.ex--p3bfo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m18 10 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k00r0bcel) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 13h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l5r0hwbum) {
  d: path("m18 10 3 3 -3 3");
}

:global(.p1-4htbpj) {
  d: path("m10 4 -6 6 6 6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.zu8e5tltb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 4 -6 6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
