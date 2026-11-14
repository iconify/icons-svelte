<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er1t1bbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:microphone-live" {...props}></Icon>
<style>
:global(.er1t1bbdy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5za3 3 0 0 1 3 3V11a3 3 0 0 1-3 3a3 3 0 0 1-3-3V5.5a3 3 0 0 1 3-3M12 14v7m-3 0h6m-7.243-8.507a6 6 0 0 1 0-8.486m8.486 0a6 6 0 0 1 0 8.486M4.218 13.699a9.5 9.5 0 0 1 0-10.898m15.564 0a9.5 9.5 0 0 1 0 10.898");
}

</style>
