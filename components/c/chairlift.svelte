<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jq2ha0b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chairlift" {...props}></Icon>
<style>
:global(.jq2ha0b9s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.75 6.25l18.5-3.5M7.75 5.3V10m7.5 7v3.5h3M7 10h1.5q1 0 1 1v1.75q0 1 1 1H16q1 0 1 1V16q0 1-1 1H7q-1 0-1-1v-5q0-1 1-1");
}

</style>
