<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ce-48-bek"/><path class="s8lfmtbgm"/><path class="s1ev1ubdz"/><path class="f8wj1yoym"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:forward-duotone-thin" {...props}></Icon>
<style>
:global(.ce-48-bek) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 4 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f8wj1yoym) {
  d: path("M21 9H7v11");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s1ev1ubdz) {
  d: path("m16 4 5 5 -5 5");
}

:global(.s8lfmtbgm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 9H7v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
