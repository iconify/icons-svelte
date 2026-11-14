<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="val1jn_gl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:recovery-path" {...props}></Icon>
<style>
:global(.val1jn_gl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5h5v-5h5v-5h9m-7-6a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
