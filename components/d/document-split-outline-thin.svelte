<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bp9na9-yx"/><path class="vl0d0wtss"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:document-split-outline-thin" {...props}></Icon>
<style>
:global(.bp9na9-yx) {
  d: path("M10 3H4v16h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vl0d0wtss) {
  d: path("M14 5h6v16h-6");
}

</style>
