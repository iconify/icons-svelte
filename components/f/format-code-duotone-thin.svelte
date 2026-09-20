<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ck7sgubpk"/><path class="wbgks6aps"/><path class="d4p-kbtat"/><path class="hsnj9o-9y"/><path class="k6nj2fbya"/><path class="rhp6fjekz"/><path class="a-768stfr"/><path class="jkuojibnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:format-code-duotone-thin" {...props}></Icon>
<style>
:global(.a-768stfr) {
  d: path("M8 15h13");
}

:global(.ck7sgubpk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d4p-kbtat) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 15h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hsnj9o-9y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.rhp6fjekz) {
  d: path("M8 10h13");
}

:global(.wbgks6aps) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 10h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
