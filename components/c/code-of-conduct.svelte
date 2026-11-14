<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxd3clb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:code-of-conduct" {...props}></Icon>
<style>
:global(.oxd3clb4e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5v-14a4 4 0 0 1 8 0v14Zm11 0v-14a4 4 0 0 1 8 0v14Zm-8.25-11h2.5M5.25 14h2.5m-2.5 3.5h2.5m8.5-7h2.5m-2.5 3.5h2.5m-2.5 3.5h2.5");
}

</style>
