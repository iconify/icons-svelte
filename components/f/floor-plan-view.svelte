<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mpxn8hb0s"/><path class="qqipvh25z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:floor-plan-view" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mpxn8hb0s) {
  d: path("M4.75 3h14.5A1.75 1.75 0 0 1 21 4.75v14.5A1.75 1.75 0 0 1 19.25 21H4.75A1.75 1.75 0 0 1 3 19.25V4.75A1.75 1.75 0 0 1 4.75 3M12 3v6m0 4v8m-9-9h5");
}

:global(.qqipvh25z) {
  d: path("M16 9a4 4 0 0 1-4 4m0-4h4");
}

</style>
