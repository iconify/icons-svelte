<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i61vc0b-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:campaign-draft" {...props}></Icon>
<style>
:global(.i61vc0b-b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.403 16.607L7.5 13.5h-4v-5h4l9.5-5v9.565M6 13.5l1.5 5m7.5 2.75l.5-2.75l3.75-3.75L21.5 17l-3.75 3.75Z");
}

</style>
