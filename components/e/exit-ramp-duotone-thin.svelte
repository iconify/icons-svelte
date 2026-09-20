<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eb-0ed8cb"/><path class="o4cycjbme"/><path class="i6dj_l9os"/><path class="q8-3-v_8e"/><path class="g5j0ssbtg"/><path class="fforjyb_s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:exit-ramp-duotone-thin" {...props}></Icon>
<style>
:global(.eb-0ed8cb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 2v19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fforjyb_s) {
  d: path("M15.5 16H19v-3.5");
}

:global(.g5j0ssbtg) {
  d: path("M6 10h7l6 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i6dj_l9os) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15.5 16H19v-3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o4cycjbme) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 10h7l6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q8-3-v_8e) {
  d: path("M6 2v19");
}

</style>
