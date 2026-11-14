<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="evozbrbur"/><path class="l3c0z21cg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:deposit-instant-access" {...props}></Icon>
<style>
:global(.evozbrbur) {
  d: path("M12.76 17.987C12.524 18 12.279 18 12 18c-.75 0-1.25 0-2-.25v1.75H7.5V17C5.25 16 4 14.25 4 12c0-3.5 3.5-6 8-6c4.371 0 7.798 2.358 7.991 5.7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l3c0z21cg) {
  d: path("M4.5 10.5h-2v3h2m3.25-2.75h.01M10.5 8.5h3m5.25 5.75L15.5 18.5H18l-.75 3.25l3.25-4.25H18Z");
}

</style>
