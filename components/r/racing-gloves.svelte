<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aybv3fbhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:racing-gloves" {...props}></Icon>
<style>
:global(.aybv3fbhe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 15.25v-3L4.5 10A1.75 1.75 0 0 1 7 7.5V5.75a2.5 2.5 0 0 1 5 0a2.5 2.5 0 0 1 5 0v9.5m-11 0h12l1.5 5.5h-15Zm6-9.5V9");
}

</style>
