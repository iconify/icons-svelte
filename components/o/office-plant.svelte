<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iq9fa7bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:office-plant" {...props}></Icon>
<style>
:global(.iq9fa7bmi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 14.25V3.5M9.25 14.25C9 11 8 8.75 6.25 7m8.5 7.25C15 11 16 8.75 17.75 7m-11.5 7.25h11.5l-1 6a1.25 1.25 0 0 1-1.25 1h-7a1.25 1.25 0 0 1-1.25-1Z");
}

</style>
