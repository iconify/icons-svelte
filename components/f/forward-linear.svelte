<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whd7w6bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:forward-linear" {...props}></Icon>
<style>
:global(.whd7w6bie) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 17L19.5 12L14.5 7M19.5 12L9.5 12C7.83333 12 4.5 13 4.5 17");
}

</style>
