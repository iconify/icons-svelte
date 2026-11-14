<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iw49jcbqb"/><path class="gjzoqze8y"/><path class="ite58wb9m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:blood-vessel-section" {...props}></Icon>
<style>
:global(.gjzoqze8y) {
  d: path("M8 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ite58wb9m) {
  d: path("M9.606 18.578a7 7 0 0 1 0-13.156m4.788 0a7 7 0 0 1 0 13.156");
}

:global(.iw49jcbqb) {
  d: path("M2.25 12a9.75 9.75 0 1 0 19.5 0a9.75 9.75 0 1 0-19.5 0");
}

</style>
