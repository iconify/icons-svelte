<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="idi-ydbun"/><path class="w6z16cc7t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:capsule-reentry" {...props}></Icon>
<style>
:global(.idi-ydbun) {
  d: path("M9 3.5h6l4.5 9a12 12 0 0 1-15 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w6z16cc7t) {
  d: path("M10.5 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM8 17.5L7 21m5-3v3.5m4-4l1 3.5");
}

</style>
