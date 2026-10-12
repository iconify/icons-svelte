<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4p1-gbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cactus" {...props}></Icon>
<style>
:global(.a4p1-gbti) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 21.25v-16a2.5 2.5 0 0 1 5 0v16Zm0-6.5h-2a2.25 2.25 0 0 1-2.25-2.25V9m9.25 3h2a2.25 2.25 0 0 0 2.25-2.25V7m-12 14.25h10.5");
}

</style>
