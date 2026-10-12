<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo_b0b69o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:prison-bars" {...props}></Icon>
<style>
:global(.zo_b0b69o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.25h18.5m-18.5 17.5h18.5M5.5 3.25v17.5m4.25-17.5v17.5m4.5-17.5v17.5m4.25-17.5v17.5m-13-9.5h13");
}

</style>
