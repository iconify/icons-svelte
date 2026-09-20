<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pyt73z1yp"/><path class="xhfvy9skf"/><path class="mhvizraib"/><path class="dmkbrpb4f"/><path class="m1mjigbsi"/><path class="ml3aqbbkk"/><path class="t1tm72bkp"/><path class="zyvg9rbxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:high-jump-duotone-regular" {...props}></Icon>
<style>
:global(.dmkbrpb4f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 15c2 -7 10 -7 12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m1mjigbsi) {
  d: path("M4 8h16");
}

:global(.mhvizraib) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ml3aqbbkk) {
  d: path("M4 8v12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pyt73z1yp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 8h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t1tm72bkp) {
  d: path("M20 8v12");
}

:global(.xhfvy9skf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zyvg9rbxb) {
  d: path("M6 15c2 -7 10 -7 12 0");
}

</style>
