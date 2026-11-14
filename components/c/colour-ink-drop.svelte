<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vusmdybgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:colour-ink-drop" {...props}></Icon>
<style>
:global(.vusmdybgm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5s-5.5 6-5.5 10a5.5 5.5 0 0 0 11 0c0-4-5.5-10-5.5-10M2.5 21h19M3 15.5l1.5 2.25M21 15.5l-1.5 2.25");
}

</style>
