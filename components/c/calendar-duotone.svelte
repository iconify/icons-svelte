<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f9hoyynpq"/><path class="nkg7s7ybl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:calendar-duotone" {...props}></Icon>
<style>
:global(.f9hoyynpq) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 4H18C20.2091 4 22 5.79086 22 8V18C22 20.2091 20.2091 22 18 22H6C3.79086 22 2 20.2091 2 18V8C2 5.79086 3.79086 4 6 4Z");
  stroke: none;
}

:global(.nkg7s7ybl) {
  d: path("M7 11L17 11M8 3L8 7M16 3L16 7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
