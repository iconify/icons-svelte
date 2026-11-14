<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvmjwdbuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:barber-chair" {...props}></Icon>
<style>
:global(.dvmjwdbuw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 3.5V14h10m-10-4h8m-2.5 4v6.5m-4 0h8m.5-6.5l2.5 4h2");
}

</style>
