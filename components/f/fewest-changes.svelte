<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cegsy7bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fewest-changes" {...props}></Icon>
<style>
:global(.cegsy7bcn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 19.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm14.5-14.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-11 13L10 14m4-4l3.75-3.75M9.25 12a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

</style>
