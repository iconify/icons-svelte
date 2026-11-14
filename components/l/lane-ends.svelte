<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcjc1gb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lane-ends" {...props}></Icon>
<style>
:global(.hcjc1gb3u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21.5v-19m16 19V14l-7-7V2.5m-1 19v-4m0-3V11");
}

</style>
