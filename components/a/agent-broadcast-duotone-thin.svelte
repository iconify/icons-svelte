<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bawbsacxs"/><path class="nzmbqmj4d"/><path class="f_vwbjhhu"/><path class="yodmvm0rk"/><path class="rdu4rh63r"/><path class="v_swcusij"/><path class="gjq7qdjci"/><path class="wm3wqu-9e"/><path class="lf7-wkbzn"/><path class="zllo9xxih"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-broadcast-duotone-thin" {...props}></Icon>
<style>
:global(.bawbsacxs) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.27 9.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f_vwbjhhu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.75 17.63a6.5 6.5 0 0 1 0 -11.26");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gjq7qdjci) {
  d: path("M15.25 6.37a6.5 6.5 0 0 1 0 11.26");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lf7-wkbzn) {
  d: path("M17 3.34a10 10 0 0 1 0 17.32");
}

:global(.nzmbqmj4d) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15.25 6.37a6.5 6.5 0 0 1 0 11.26");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rdu4rh63r) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 20.66A10 10 0 0 1 7 3.34");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v_swcusij) {
  d: path("M13.27 9.28a3 3 0 1 1 -2.54 0");
}

:global(.wm3wqu-9e) {
  d: path("M8.75 17.63a6.5 6.5 0 0 1 0 -11.26");
}

:global(.yodmvm0rk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 3.34a10 10 0 0 1 0 17.32");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zllo9xxih) {
  d: path("M7 20.66A10 10 0 0 1 7 3.34");
}

</style>
