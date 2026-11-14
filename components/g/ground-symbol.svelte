<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuozipb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ground-symbol" {...props}></Icon>
<style>
:global(.tuozipb9d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4v7m-8 0h16M7 15.5h10M10 20h4");
}

</style>
