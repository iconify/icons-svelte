<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xwlcmyxvb"/><path class="ydao2826v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:boat-lift" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xwlcmyxvb) {
  d: path("M3.5 21V3.5h17V21");
}

:global(.ydao2826v) {
  d: path("M12 3.5v6M7.5 13L12 9.5l4.5 3.5m-10 0h11l-1.75 4.5h-7.5Z");
}

</style>
