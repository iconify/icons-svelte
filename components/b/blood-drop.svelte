<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="og97qruha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:blood-drop" {...props}></Icon>
<style>
:global(.og97qruha) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3c2.25 3 6 7.1 6 10.75a6 6 0 0 1-12 0C6 10.1 9.75 6 12 3m0 8.25v5m-2.5-2.5h5");
}

</style>
