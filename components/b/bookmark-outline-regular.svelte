<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngdce-bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bookmark-outline-regular" {...props}></Icon>
<style>
:global(.ngdce-bab) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 3h3v18l-6 -6 -6 6V3h3");
}

</style>
