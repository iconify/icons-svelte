<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0cwj2-md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:moon-gibbous" {...props}></Icon>
<style>
:global(.o0cwj2-md) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75a9.25 9.25 0 0 1 0 18.5a4.75 9.25 0 0 1 0-18.5M6.05 4.91a9.25 9.25 0 0 0 0 14.18");
}

</style>
