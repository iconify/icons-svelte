<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="v6vao-e4h"/><path class="od0vipp_m"/><path class="iumduw1da"/><path class="v-jogvb5z"/><path class="weeetziwb"/><path class="qydoy8byr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:event-failed-duotone-bold" {...props}></Icon>
<style>
:global(.iumduw1da) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m19 10 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.od0vipp_m) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14 10 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qydoy8byr) {
  d: path("m19 10 -5 5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v-jogvb5z) {
  d: path("m10 6 -5 5h4l-5 5");
}

:global(.v6vao-e4h) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 6 -5 5h4l-5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.weeetziwb) {
  d: path("m14 10 5 5");
}

</style>
