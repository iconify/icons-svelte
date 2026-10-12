<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xd4lgccmv"/><path class="kka-q1blt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:blood-pressure" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kka-q1blt) {
  d: path("M7.75 14.25a4.25 4.25 0 0 1 8.5 0m-4.25 0l2.25-2.75");
}

:global(.xd4lgccmv) {
  d: path("M12 20.5c-4.75-3.25-8.75-6.5-8.75-11A4.55 4.55 0 0 1 12 7.25a4.55 4.55 0 0 1 8.75 2.25c0 4.5-4 7.75-8.75 11");
}

</style>
