<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l7lis87jb"/><path class="t0tr22eyz"/><path class="k_gogwbfe"/><path class="joid91atd"/><path class="m1mjigbsi"/><path class="ml3aqbbkk"/><path class="t1tm72bkp"/><path class="zyvg9rbxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:high-jump-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.joid91atd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 15c2 -7 10 -7 12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k_gogwbfe) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l7lis87jb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 8h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m1mjigbsi) {
  d: path("M4 8h16");
}

:global(.ml3aqbbkk) {
  d: path("M4 8v12");
}

:global(.t0tr22eyz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t1tm72bkp) {
  d: path("M20 8v12");
}

:global(.zyvg9rbxb) {
  d: path("M6 15c2 -7 10 -7 12 0");
}

</style>
