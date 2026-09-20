<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pux-8e3tz"/><path class="wkp4c939u"/><path class="hvq_ui2bc"/><path class="cacmi2bmi"/><path class="ffipo4b5s"/><path class="mut__fbgb"/><path class="c8uh2gw9u"/><path class="krno6ds-i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:container-file-duotone-thin" {...props}></Icon>
<style>
:global(.c8uh2gw9u) {
  d: path("M9 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.cacmi2bmi) {
  d: path("M13 3H9L6 6v15h12V8");
}

:global(.ffipo4b5s) {
  d: path("M9 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hvq_ui2bc) {
  fill: currentColor;
  d: path("M9 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.krno6ds-i) {
  d: path("M13 15h3");
}

:global(.mut__fbgb) {
  d: path("M13 11h3");
}

:global(.pux-8e3tz) {
  fill: currentColor;
  d: path("M13 3H9L6 6v15h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wkp4c939u) {
  fill: currentColor;
  d: path("M9 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
