<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fftpptbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:end-mill" {...props}></Icon>
<style>
:global(.fftpptbgn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 2.5h1.5a1.75 1.75 0 0 1 1.75 1.75v4.5a1.75 1.75 0 0 1-1.75 1.75h-1.5A1.75 1.75 0 0 1 9.5 8.75v-4.5a1.75 1.75 0 0 1 1.75-1.75m-1.75 8V19l2.5 2.5l2.5-2.5v-8.5m-5 3.5l5-2m-5 5.5l5-2");
}

</style>
