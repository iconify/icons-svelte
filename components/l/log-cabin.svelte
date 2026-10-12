<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6-f66bhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:log-cabin" {...props}></Icon>
<style>
:global(.i6-f66bhh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.37 8.58l8.01-5.41q.62-.42 1.24 0l8.01 5.41q.62.42-.13.42h-17q-.75 0-.13-.42M5.5 12h13a1.54 1.54 0 0 1 0 3.08a1.54 1.54 0 0 1 0 3.09a1.54 1.54 0 0 1 0 3.08h-13a1.54 1.54 0 0 1 0-3.08a1.54 1.54 0 0 1 0-3.09a1.54 1.54 0 0 1 0-3.08m0 3.08h13m-13 3.09h13");
}

</style>
