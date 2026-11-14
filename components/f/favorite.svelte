<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qp3v1ebws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:favorite" {...props}></Icon>
<style>
:global(.qp3v1ebws) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 3.75l-2 5.5l-6 .25l4.5 3.75L7 19l5-3.25m0-12l2 5.5l6 .25l-4.5 3.75L17 19l-5-3.25");
}

</style>
