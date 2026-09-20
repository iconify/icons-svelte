<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ck7sgubpk"/><path class="fx-2c_44o"/><path class="rx5svrbnh"/><path class="ujz5ulrwv"/><path class="uau0kschl"/><path class="k6nj2fbya"/><path class="a6mnjib5x"/><path class="l8vricc3a"/><path class="t8troqb7m"/><path class="yngda3bvc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:backfill-data-duotone-thin" {...props}></Icon>
<style>
:global(.a6mnjib5x) {
  d: path("M3 10h4");
}

:global(.ck7sgubpk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fx-2c_44o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 10h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.l8vricc3a) {
  d: path("M17 10h4");
}

:global(.rx5svrbnh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 10h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t8troqb7m) {
  d: path("m10 9 2 2 2 -2");
}

:global(.uau0kschl) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 15h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ujz5ulrwv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 9 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yngda3bvc) {
  d: path("M3 15h18");
}

</style>
