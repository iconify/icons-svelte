<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f-7mi-ili"/><path class="klhc1wvwx"/><path class="f33exibub"/><path class="sj9rw9tzk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:drift-duotone-thin" {...props}></Icon>
<style>
:global(.f-7mi-ili) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h9l6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.f33exibub) {
  d: path("M3 12h9l6 -6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.klhc1wvwx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 12 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sj9rw9tzk) {
  d: path("m12 12 6 6");
}

</style>
