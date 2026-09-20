<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jkfk4gb_o"/><path class="m8ek3-bfo"/><path class="eisa2cb9u"/><path class="o7l5jxuid"/><path class="hmmgrhbhr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:landing-duotone-thin" {...props}></Icon>
<style>
:global(.eisa2cb9u) {
  d: path("M2 22h20");
}

:global(.hmmgrhbhr) {
  d: path("M2 5h3V2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jkfk4gb_o) {
  fill: currentColor;
  d: path("m12 3 2 2v4l5.5 5.5H14V17l2 2H8l2 -2v-2.5H4.5L10 9V5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.m8ek3-bfo) {
  d: path("m12 3 2 2v4l5.5 5.5H14V17l2 2H8l2 -2v-2.5H4.5L10 9V5Z");
}

:global(.o7l5jxuid) {
  d: path("m2 2 3 3");
}

</style>
