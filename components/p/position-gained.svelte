<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vr1zmhbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:position-gained" {...props}></Icon>
<style>
:global(.vr1zmhbtr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5H8v-4h8v4h5.5m-9.5-7V4M7.5 8.5L12 4l4.5 4.5");
}

</style>
