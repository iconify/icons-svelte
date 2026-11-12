<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0xwtobcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:forward-2-linear" {...props}></Icon>
<style>
:global(.o0xwtobcp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 7L19.5 12L14.5 17M19.5 12L9.5 12C7.83333 12 4.5 11 4.5 7");
}

</style>
