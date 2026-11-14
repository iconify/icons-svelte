<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yi4evlbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cattle-grid" {...props}></Icon>
<style>
:global(.yi4evlbfw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8 2.5l-4.75 19M16 2.5l4.75 19m-14.5-12h11.5m-12.25 3h13m-13.75 3h14.5M12 2.5v4m0 12v3");
}

</style>
