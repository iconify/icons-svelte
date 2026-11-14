<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfvlu3jcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cloud-hail" {...props}></Icon>
<style>
:global(.vfvlu3jcr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 15.5a4 4 0 0 1 0-8a5.5 5.5 0 0 1 11 1a3.5 3.5 0 0 1-1 7Zm-.5 4a1 1 0 1 0 2 0a1 1 0 1 0-2 0m4.5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0m4.5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
