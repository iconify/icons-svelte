<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o41eah0bw"/><path class="lgv7os48g"/><path class="iygpkbb2j"/><path class="eh2tvmfpp"/><path class="b-omsu8gz"/><path class="azjtlhb3x"/><path class="o8od38cnm"/><path class="hiqcqfbaf"/><path class="rqk3146zh"/><path class="uysczfb3e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:island-duotone-thin" {...props}></Icon>
<style>
:global(.azjtlhb3x) {
  d: path("M4 18a8 8 0 0 1 16 0");
}

:global(.b-omsu8gz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 11a3 3 0 0 1 0 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.eh2tvmfpp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 5a3 3 0 0 1 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hiqcqfbaf) {
  d: path("M12 8v10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iygpkbb2j) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 8v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lgv7os48g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 18h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o41eah0bw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 18a8 8 0 0 1 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o8od38cnm) {
  d: path("M4 18h16");
}

:global(.rqk3146zh) {
  d: path("M9 5a3 3 0 0 1 0 6");
}

:global(.uysczfb3e) {
  d: path("M15 11a3 3 0 0 1 0 -6");
}

</style>
