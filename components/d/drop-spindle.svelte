<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqwm5bb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:drop-spindle" {...props}></Icon>
<style>
:global(.sqwm5bb_v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19m0-17c5.5 2 5.5 6 0 8c-5.5-2-5.5-6 0-8ZM5 18a7 2.5 0 1 0 14 0a7 2.5 0 1 0-14 0Z");
}

</style>
