<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm8ttjbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gas-cylinder" {...props}></Icon>
<style>
:global(.zm8ttjbtx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 21.5v-12a4.5 4.5 0 0 1 9 0v12ZM12 5V2.5m-2.5 0h5");
}

</style>
