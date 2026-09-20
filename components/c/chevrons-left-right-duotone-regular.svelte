<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s8_kr602n"/><path class="i59idob3x"/><path class="s6jbysbtk"/><path class="h-_fm4bbo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chevrons-left-right-duotone-regular" {...props}></Icon>
<style>
:global(.h-_fm4bbo) {
  d: path("m15 7 5 5 -5 5");
}

:global(.i59idob3x) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m15 7 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s6jbysbtk) {
  d: path("m9 7 -5 5 5 5");
}

:global(.s8_kr602n) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 7 -5 5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
