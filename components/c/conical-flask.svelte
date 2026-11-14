<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd2vrwufc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:conical-flask" {...props}></Icon>
<style>
:global(.dd2vrwufc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3v6.25l-5.25 9.5C4.25 19.9 4.9 21 6.2 21h11.6c1.3 0 1.95-1.1 1.45-2.25L14 9.25V3M9 3h6M7.75 15.5h8.5");
}

</style>
