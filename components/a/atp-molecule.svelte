<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="an1m7sbhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:atp-molecule" {...props}></Icon>
<style>
:global(.an1m7sbhr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.059 12.756l-.875 1.5A1.5 1.5 0 0 1 6.888 15H5.112a1.5 1.5 0 0 1-1.296-.744l-.875-1.5a1.5 1.5 0 0 1 0-1.512l.875-1.5A1.5 1.5 0 0 1 5.112 9h1.776a1.5 1.5 0 0 1 1.296.744l.875 1.5a1.5 1.5 0 0 1 0 1.512M9.5 12h1a1.5 1.5 0 1 1 3 0a1.5 1.5 0 1 1-3 0m3 0h1a1.5 1.5 0 1 1 3 0a1.5 1.5 0 1 1-3 0m3 0h1a1.5 1.5 0 1 1 3 0a1.5 1.5 0 1 1-3 0");
}

</style>
