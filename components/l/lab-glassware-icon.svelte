<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3rh8zb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lab-glassware-icon" {...props}></Icon>
<style>
:global(.a3rh8zb2t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9v9.5a1.5 1.5 0 0 0 3 0V9M11 3.5v6l-2.5 9.75a1 1 0 0 0 1 1.25h5a1 1 0 0 0 1-1.25L13 9.5v-6M18.5 9v11.5h3V9");
}

</style>
