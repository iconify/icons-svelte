<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fus-_gbgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chevrons-left" {...props}></Icon>
<style>
:global(.fus-_gbgz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 17.5L6 12l5.5-5.5m6 11L12 12l5.5-5.5");
}

</style>
