<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cn_1flbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ramp-portable" {...props}></Icon>
<style>
:global(.cn_1flbsa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.049 13.22l11.169-6.825a1.5 1.5 0 0 1 2.282 1.28V14.5A1.5 1.5 0 0 1 19 16H7.831a1.5 1.5 0 0 1-.782-2.78M2.5 19h19");
}

</style>
