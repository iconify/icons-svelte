<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g6n49udox"/><path class="pwcdu7b1o"/><path class="j6jqp97zs"/><path class="n_h_kpigg"/><path class="h2-2dgnfu"/><path class="sm02sv71h"/><path class="gtujb54ma"/><path class="g_k4zfu5d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:diff-duotone-thin" {...props}></Icon>
<style>
:global(.g_k4zfu5d) {
  d: path("M14 15h6");
}

:global(.g6n49udox) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gtujb54ma) {
  d: path("M4 9h6");
}

:global(.h2-2dgnfu) {
  d: path("M12 3v18");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j6jqp97zs) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n_h_kpigg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 15h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pwcdu7b1o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 6v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sm02sv71h) {
  d: path("M7 6v6");
}

</style>
