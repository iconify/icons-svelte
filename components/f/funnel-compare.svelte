<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gv46rsb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:funnel-compare" {...props}></Icon>
<style>
:global(.gv46rsb5v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5h6.75L7 11.5V19l-2.25-1.5v-6Zm12.25 0h6.75l-2.25 6.5V19L17 17.5v-6ZM12 3v18");
}

</style>
