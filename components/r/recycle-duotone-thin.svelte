<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="toegp3o3w"/><path class="b3zkugbuv"/><path class="q_2x4objc"/><path class="sj4savk2e"/><path class="t85xi9o1t"/><path class="mlzwc7b5b"/><path class="kd8pirhpr"/><path class="crw18vrkk"/><path class="z-xixkiyt"/><path class="hspeog_hs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:recycle-duotone-thin" {...props}></Icon>
<style>
:global(.b3zkugbuv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12.5 6.5 15 9l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.crw18vrkk) {
  d: path("m18 14 -5 5H9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hspeog_hs) {
  d: path("m7 18 -4 -4 4 -4");
}

:global(.kd8pirhpr) {
  d: path("M12.5 6.5 15 9l-2.5 2.5");
}

:global(.mlzwc7b5b) {
  d: path("m6 14 5 -5h4");
}

:global(.q_2x4objc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m18 14 -5 5H9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sj4savk2e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11.5 16.5 9 19l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t85xi9o1t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 18 -4 -4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.toegp3o3w) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 14 5 -5h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z-xixkiyt) {
  d: path("M11.5 16.5 9 19l2.5 2.5");
}

</style>
