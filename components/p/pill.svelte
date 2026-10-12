<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="we246k-fy"/><path class="iz8sjwb3r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pill" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iz8sjwb3r) {
  d: path("m9.53 9.53l4.24-4.25a3.5 3.5 0 0 1 4.95 4.95l-4.25 4.24Z");
}

:global(.we246k-fy) {
  d: path("m9.53 9.53l-4.25 4.24a3.5 3.5 0 0 0 4.95 4.95l4.24-4.25Z");
}

</style>
