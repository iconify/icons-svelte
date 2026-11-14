<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2dlhbcdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:knuckles" {...props}></Icon>
<style>
:global(.j2dlhbcdj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7a2.25 2.25 0 0 1 4.5 0A2.25 2.25 0 0 1 12 7a2.25 2.25 0 0 1 4.5 0A2.25 2.25 0 0 1 21 7v8c0 3-2.5 5-5.5 5h-7c-3 0-5.5-2-5.5-5Zm4.5 0v3.5M12 7v3.5M16.5 7v3.5M3 14h9.5");
}

</style>
