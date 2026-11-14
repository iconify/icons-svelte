<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mr177ccqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:brick-wall" {...props}></Icon>
<style>
:global(.mr177ccqu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h19m-19 17h19M2.5 9.25h19m-19 5.5h19M12 3.5v5.75m-5 0v5.5m10-5.5v5.5m-5 0v5.75");
}

</style>
