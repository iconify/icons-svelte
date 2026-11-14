<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyh4npb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mixing-bowl" {...props}></Icon>
<style>
:global(.fyh4npb1c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9.5h18c0 6-4 10.5-9 10.5S3 15.5 3 9.5m5-4h8");
}

</style>
