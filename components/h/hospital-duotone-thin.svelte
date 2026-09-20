<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jgzhtab3b"/><path class="vj-1ubcjx"/><path class="t0-mwc0xy"/><path class="zka_zabrc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hospital-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jgzhtab3b) {
  fill: currentColor;
  d: path("M4 20V7h16v13Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.t0-mwc0xy) {
  d: path("M12 10v6");
}

:global(.vj-1ubcjx) {
  d: path("M4 20V7h16v13Z");
}

:global(.zka_zabrc) {
  d: path("M9 13h6");
}

</style>
