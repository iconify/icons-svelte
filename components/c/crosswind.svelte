<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7atejbgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:crosswind" {...props}></Icon>
<style>
:global(.k7atejbgh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.5 21V3M13 6.5L16.5 3L20 6.5M3.5 10h9m-9 5h9");
}

</style>
