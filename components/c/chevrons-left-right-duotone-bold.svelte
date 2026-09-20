<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="facqd0bly"/><path class="e75ly3b0v"/><path class="s6jbysbtk"/><path class="h-_fm4bbo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chevrons-left-right-duotone-bold" {...props}></Icon>
<style>
:global(.e75ly3b0v) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 7 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.facqd0bly) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 7 -5 5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h-_fm4bbo) {
  d: path("m15 7 5 5 -5 5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s6jbysbtk) {
  d: path("m9 7 -5 5 5 5");
}

</style>
