<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ppk8qz4nb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chord-diagram" {...props}></Icon>
<style>
:global(.ppk8qz4nb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.16 3.31a9.25 9.25 0 0 1 5.95 10.3m-18.22 0a9.25 9.25 0 0 1 5.95-10.3m9.11 15.78a9.25 9.25 0 0 1-11.9 0m12.53-9.48Q12 12 15.5 18.06m-7 0Q12 12 5 12m3.5-6.06q3.5 6.06 7 0");
}

</style>
