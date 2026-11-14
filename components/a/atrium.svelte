<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ic8gzqb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:atrium" {...props}></Icon>
<style>
:global(.ic8gzqb0o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21V8h5l4-4.5L16 8h5v13ZM8 8v13m8-13v13");
}

</style>
