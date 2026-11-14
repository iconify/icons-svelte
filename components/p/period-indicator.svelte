<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd6u9abmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:period-indicator" {...props}></Icon>
<style>
:global(.jd6u9abmd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.563 3.137a9 9 0 0 1 7.3 7.3m0 3.126a9 9 0 0 1-7.3 7.3m-3.126 0a9 9 0 0 1-7.3-7.3m0-3.126a9 9 0 0 1 7.3-7.3M12 12h.01");
}

</style>
