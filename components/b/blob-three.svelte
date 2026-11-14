<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aildqlfas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:blob-three" {...props}></Icon>
<style>
:global(.aildqlfas) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 10.25a5.5 5.5 0 1 1 10 0A5.5 5.5 0 1 1 12 19a5.5 5.5 0 1 1-5-8.75");
}

</style>
