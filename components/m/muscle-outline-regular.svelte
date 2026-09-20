<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ad299no4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:muscle-outline-regular" {...props}></Icon>
<style>
:global(.ad299no4m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 21v-5c0 -4 4 -7 8 -5 1 0.5 2 1.5 2 3V9c0 -3 3 -5 5 -3s2 6 1 9 -3 6 -7 6Z");
}

</style>
