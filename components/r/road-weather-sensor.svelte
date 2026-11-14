<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjns5pbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:road-weather-sensor" {...props}></Icon>
<style>
:global(.pjns5pbnn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 3h4.5A1.75 1.75 0 0 1 16 4.75v2.5A1.75 1.75 0 0 1 14.25 9h-4.5A1.75 1.75 0 0 1 8 7.25v-2.5A1.75 1.75 0 0 1 9.75 3M12 9v9.5m-9 0h18m-18 3h18M12 6h.01");
}

</style>
