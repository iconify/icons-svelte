<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmk8llbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:kung-fu-shoes" {...props}></Icon>
<style>
:global(.vmk8llbqp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.5v-5C2.5 11 3.5 10 5 10s3 2 5.5 2c3.5 0 6.5-1.5 11-5c0 6.5-2 10.5-5.5 10.5Zm0-2.75h17.25");
}

</style>
