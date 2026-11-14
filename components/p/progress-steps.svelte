<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxkt8-f8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:progress-steps" {...props}></Icon>
<style>
:global(.lxkt8-f8r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0H10m0 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0h3.5m0 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
