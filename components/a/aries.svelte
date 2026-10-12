<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxi0jx9ip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:aries" {...props}></Icon>
<style>
:global(.oxi0jx9ip) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.25c0-3-1.75-5-4.25-5s-4 1.75-4 4s1 3 2 3.25M12 9.25c0-3 1.75-5 4.25-5s4 1.75 4 4s-1 3-2 3.25M12 9.25v11");
}

</style>
