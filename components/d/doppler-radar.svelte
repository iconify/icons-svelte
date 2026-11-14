<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx-s5cb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:doppler-radar" {...props}></Icon>
<style>
:global(.lx-s5cb_t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 13a4 4 0 0 1 8 0Zm1 8.5l3-8.5l3 8.5M12 7a7 7 0 0 1 3.5 4.75M13.75 4a10.5 10.5 0 0 1 5 7.25");
}

</style>
