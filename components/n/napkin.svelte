<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_l12lblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:napkin" {...props}></Icon>
<style>
:global(.n_l12lblt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 20.5l-8.25-16a2.75 1.5 0 0 1 5.5 0a2.75 1.5 0 0 1 5.5 0a2.75 1.5 0 0 1 5.5 0Zm-1.5-8L9.25 7m4.25 5.5L14.75 7m-9.5 13.5h13.5");
}

</style>
