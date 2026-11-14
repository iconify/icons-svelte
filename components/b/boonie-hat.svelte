<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmpqkv2ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:boonie-hat" {...props}></Icon>
<style>
:global(.lmpqkv2ca) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 14v-3a5.5 5.5 0 0 1 11 0v3m-15 4.5Q3 14 6.5 14h11q3.5 0 4 4.5M6.5 11h11");
}

</style>
