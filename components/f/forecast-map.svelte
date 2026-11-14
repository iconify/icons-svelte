<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b-n2ypbax"/><path class="nafvathas"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:forecast-map" {...props}></Icon>
<style>
:global(.b-n2ypbax) {
  d: path("M10.728 19.796L8.5 19l-6 2.5V5l6-2.5l7 2.5l6-2.5v12.467M8.5 2.5V19m7-14v9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nafvathas) {
  d: path("M15.5 21.5a2 2 0 0 1 0-4a2.75 2.75 0 0 1 4.75.5a1.75 1.75 0 0 1-.25 3.5Z");
}

</style>
