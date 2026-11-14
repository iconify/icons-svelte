<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z147_-bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:coding-test" {...props}></Icon>
<style>
:global(.z147_-bvl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 6l-4.5 6L7 18M17 6l4.5 6l-4.5 6m-8-5.75l2.25 2.25l3.75-5");
}

</style>
