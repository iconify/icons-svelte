<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bw6cpcvfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:galley-container" {...props}></Icon>
<style>
:global(.bw6cpcvfj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 18.5v-12A3.5 3.5 0 0 1 8 3h6a3.5 3.5 0 0 1 3.5 3.5v12Zm0-11h13m0 3h2.25V15H17.5m-10 6.25h.01m6.99 0h.01");
}

</style>
