<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q8iaooblc"/><path class="mdg-xhg5c"/><path class="sfyvujw3a"/><path class="yg83_ebrk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dimension-reduce-duotone-bold" {...props}></Icon>
<style>
:global(.mdg-xhg5c) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m18.5 14 2.5 2.5 -4 4 -4 -4 2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q8iaooblc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m13 4 4 4 -6.5 6.5L4 8l4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sfyvujw3a) {
  d: path("m13 4 4 4 -6.5 6.5L4 8l4 -4");
}

:global(.yg83_ebrk) {
  d: path("m18.5 14 2.5 2.5 -4 4 -4 -4 2.5 -2.5");
}

</style>
