<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oqqpslo4a"/><path class="ixy085bpz"/><path class="ogpcbjbkq"/><path class="fa6o0ub5s"/><path class="ytqok-bxz"/><path class="gorvssbqo"/><path class="e6cqo_biq"/><path class="kliut9bht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:greedy-decode-duotone-thin" {...props}></Icon>
<style>
:global(.e6cqo_biq) {
  d: path("m6 12 5 -5");
}

:global(.fa6o0ub5s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 12 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gorvssbqo) {
  d: path("M17.5 9.5 20 12l-2.5 2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ixy085bpz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17.5 9.5 20 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kliut9bht) {
  d: path("m10 12 5 5");
}

:global(.ogpcbjbkq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 12 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oqqpslo4a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h15.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ytqok-bxz) {
  d: path("M2 12h15.5");
}

</style>
