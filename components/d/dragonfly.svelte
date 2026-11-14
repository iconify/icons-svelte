<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1gqz0bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dragonfly" {...props}></Icon>
<style>
:global(.k1gqz0bwm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M12 6.75V21.5m-9.5-12a4.75 1.75 0 1 0 9.5 0a4.75 1.75 0 1 0-9.5 0m9.5 0a4.75 1.75 0 1 0 9.5 0a4.75 1.75 0 1 0-9.5 0m-9 6a4.5 1.75 0 1 0 9 0a4.5 1.75 0 1 0-9 0m9 0a4.5 1.75 0 1 0 9 0a4.5 1.75 0 1 0-9 0");
}

</style>
