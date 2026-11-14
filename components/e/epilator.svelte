<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2iq2ybhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:epilator" {...props}></Icon>
<style>
:global(.t2iq2ybhr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 5.5h10a2 2 0 0 1 2 2a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2a2 2 0 0 1 2-2m.5-3v3m3-3v3m3-3v3m3-3v3m-8 4V19a2.5 2.5 0 0 0 2.5 2.5h2a2.5 2.5 0 0 0 2.5-2.5V9.5M12 13v3");
}

</style>
