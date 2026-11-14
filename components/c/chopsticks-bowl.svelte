<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgnwyacra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chopsticks-bowl" {...props}></Icon>
<style>
:global(.bgnwyacra) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h19a9.5 8 0 0 1-19 0M9 12l7.5-9.5M13 12l8-8");
}

</style>
