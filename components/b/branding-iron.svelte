<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-j9adb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:branding-iron" {...props}></Icon>
<style>
:global(.v-j9adb7d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.452 18.677l2.475-2.475a1.5 1.5 0 0 1 2.121 0a1.5 1.5 0 0 1 0 2.121l-2.475 2.475a1.5 1.5 0 0 1-2.121 0a1.5 1.5 0 0 1 0-2.121M8.25 16l7.5-7.5m.689-5.286l4.597 4.597a1.75 1.75 0 0 1 0 2.475a1.75 1.75 0 0 1-2.475 0l-4.597-4.597a1.75 1.75 0 0 1 0-2.475a1.75 1.75 0 0 1 2.475 0");
}

</style>
