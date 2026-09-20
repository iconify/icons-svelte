<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n9z8gubzo"/><path class="dv40gzb0l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:learning-rate-duotone-thin" {...props}></Icon>
<style>
:global(.dv40gzb0l) {
  d: path("M3 5h5v5h5v5h5v5h3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n9z8gubzo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h5v5h5v5h5v5h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
