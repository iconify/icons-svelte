<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8fstcbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:house-power" {...props}></Icon>
<style>
:global(.e8fstcbjm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.544 20.5H3.5v-10L12 3.25l8.5 7.25v1.556M19 14.5l-3.5 3.75h5l-3.5 3.5");
}

</style>
