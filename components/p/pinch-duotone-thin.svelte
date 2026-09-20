<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hrjv8acbp"/><path class="bqgbkybbd"/><path class="mc2ku49ax"/><path class="i99bplbhq"/><path class="fpxzcl19b"/><path class="m3uk2nwvd"/><path class="v8mti3bcl"/><path class="m_x-fjbot"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pinch-duotone-thin" {...props}></Icon>
<style>
:global(.bqgbkybbd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 5.5V9H5.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fpxzcl19b) {
  d: path("m3 3 6 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hrjv8acbp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 3 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i99bplbhq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 18.5V15h3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m_x-fjbot) {
  d: path("M15 18.5V15h3.5");
}

:global(.m3uk2nwvd) {
  d: path("M9 5.5V9H5.5");
}

:global(.mc2ku49ax) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m21 21 -6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v8mti3bcl) {
  d: path("m21 21 -6 -6");
}

</style>
