<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wyo7z8nfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:door-sensor-closed" {...props}></Icon>
<style>
:global(.wyo7z8nfc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 4h1A3.5 3.5 0 0 1 12 7.5v9A3.5 3.5 0 0 1 8.5 20h-1A3.5 3.5 0 0 1 4 16.5v-9A3.5 3.5 0 0 1 7.5 4m9.75 0za2.5 2.5 0 0 1 2.5 2.5v11a2.5 2.5 0 0 1-2.5 2.5a2.5 2.5 0 0 1-2.5-2.5v-11a2.5 2.5 0 0 1 2.5-2.5M8 8h.01");
}

</style>
