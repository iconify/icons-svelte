<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zrks4nb9i"/><path class="qzgsadb6u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dovetail-joint" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qzgsadb6u) {
  d: path("M2.5 14h4l-1-5h5l-1 5h5l-1-5h5l-1 5h4");
}

:global(.zrks4nb9i) {
  d: path("M5.125 4h13.75A2.625 2.625 0 0 1 21.5 6.625v10.75A2.625 2.625 0 0 1 18.875 20H5.125A2.625 2.625 0 0 1 2.5 17.375V6.625A2.625 2.625 0 0 1 5.125 4");
}

</style>
