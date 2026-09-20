<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="esolkqbpc"/><path class="mziob6b8n"/><path class="l_e0hni9v"/><path class="ecx6lphnq"/><path class="c-pcdbceg"/><path class="s24u-_b8l"/><path class="je6wpwbmn"/><path class="t6z18wb5x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hail-duotone-thin" {...props}></Icon>
<style>
:global(.c-pcdbceg) {
  d: path("M4 14a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 5a5.5 5.5 0 0 1 4.5 9Z");
}

:global(.ecx6lphnq) {
  fill: currentColor;
  d: path("M10 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.esolkqbpc) {
  fill: currentColor;
  d: path("M4 14a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 5a5.5 5.5 0 0 1 4.5 9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.je6wpwbmn) {
  d: path("M12 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.l_e0hni9v) {
  fill: currentColor;
  d: path("M12 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mziob6b8n) {
  fill: currentColor;
  d: path("M6 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s24u-_b8l) {
  d: path("M6 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.t6z18wb5x) {
  d: path("M10 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
