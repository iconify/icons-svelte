<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8klmjb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rain-shower" {...props}></Icon>
<style>
:global(.n8klmjb0l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 6.5h13.5A1.25 1.25 0 0 1 20 7.75A1.25 1.25 0 0 1 18.75 9H5.25A1.25 1.25 0 0 1 4 7.75A1.25 1.25 0 0 1 5.25 6.5M12 4v2.5M6 12v2m4-2v2m4-2v2m4-2v2M8 17.5v2m4-2v2m4-2v2");
}

</style>
