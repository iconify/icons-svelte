<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vghh_1b0g"/><path class="k3nhh1-fh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hand-fan-pankha" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k3nhh1-fh) {
  d: path("M9.5 13.9L12 11l2.5 2.9m-2.5.35v7");
}

:global(.vghh_1b0g) {
  d: path("M12 14.25c-4.5 0-7.25-2.25-7.25-5.75S7.5 2.75 12 2.75S19.25 5 19.25 8.5S16.5 14.25 12 14.25");
}

</style>
