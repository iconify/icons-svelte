<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b8y375b7s"/><path class="htoy-r04r"/><path class="pkd2_xalb"/><path class="i13g5lbrq"/><path class="uspjb2blh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mostly-cloudy-duotone-thin" {...props}></Icon>
<style>
:global(.b8y375b7s) {
  fill: currentColor;
  d: path("M4 20a4 4 0 0 1 2 -7.5 5 5 0 0 1 9.5 -1.5 5.5 5.5 0 0 1 4.5 9Z");
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

:global(.htoy-r04r) {
  d: path("M12 6a4 4 0 0 1 8 0");
}

:global(.i13g5lbrq) {
  d: path("m22 3.5 -2 2");
}

:global(.pkd2_xalb) {
  d: path("m10 3.5 2 2");
}

:global(.uspjb2blh) {
  d: path("M4 20a4 4 0 0 1 2 -7.5 5 5 0 0 1 9.5 -1.5 5.5 5.5 0 0 1 4.5 9Z");
}

</style>
