<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xyp6wx9xg"/><path class="jej6c2f3q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cover-level-basic" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jej6c2f3q) {
  d: path("M12 9za1.75 1.75 0 0 1 1.75 1.75v8.5A1.75 1.75 0 0 1 12 21a1.75 1.75 0 0 1-1.75-1.75v-8.5A1.75 1.75 0 0 1 12 9m6.25-6zA1.75 1.75 0 0 1 20 4.75v14.5A1.75 1.75 0 0 1 18.25 21a1.75 1.75 0 0 1-1.75-1.75V4.75A1.75 1.75 0 0 1 18.25 3");
}

:global(.xyp6wx9xg) {
  fill: currentColor;
  d: path("M5.75 15za1.75 1.75 0 0 1 1.75 1.75v2.5A1.75 1.75 0 0 1 5.75 21A1.75 1.75 0 0 1 4 19.25v-2.5A1.75 1.75 0 0 1 5.75 15");
}

</style>
