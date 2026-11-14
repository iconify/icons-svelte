<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmeylwbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:portable-ramp" {...props}></Icon>
<style>
:global(.lmeylwbyt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.5 17.5v-11h6v11m-19 0h19m-19 0L7.75 13m2.5-2l5.25-4.5m-8 5.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
