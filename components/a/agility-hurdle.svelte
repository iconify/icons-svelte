<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evcb0hbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:agility-hurdle" {...props}></Icon>
<style>
:global(.evcb0hbro) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3v17.5M18 3v17.5M3.5 9.5h17m-17 11h5m7 0h5");
}

</style>
