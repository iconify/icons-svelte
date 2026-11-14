<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5ig2ezur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:concierge" {...props}></Icon>
<style>
:global(.t5ig2ezur) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 17.5a8 8 0 0 1 16 0Zm8-8v-2m-2 0h4m-11 13h18");
}

</style>
