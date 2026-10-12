<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba8boabbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:phi-sign" {...props}></Icon>
<style>
:global(.ba8boabbh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.75c4 0 6.75 2.25 6.75 5.25S16 17.25 12 17.25S5.25 15 5.25 12S8 6.75 12 6.75m0-4v18.5");
}

</style>
