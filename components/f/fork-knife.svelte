<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8prvxmdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:fork-knife" {...props}></Icon>
<style>
:global(.g8prvxmdk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 2.75v4.5a2.75 2.75 0 0 0 5.5 0v-4.5M8 2.75v18.5m7.5-6.75h-1V7.75c0-2.75 1.5-5 3.75-5h.25V19.5a1.5 1.5 0 0 1-3 0Z");
}

</style>
