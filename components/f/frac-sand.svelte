<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_o50swmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:frac-sand" {...props}></Icon>
<style>
:global(.y_o50swmd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17h19m-18 0c2-8 9-8 11 0m2.25-4.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M15 6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
