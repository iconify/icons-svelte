<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbu5-mb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:rod-of-asclepius" {...props}></Icon>
<style>
:global(.gbu5-mb1r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19m0-16c5 1 5 4 0 5s-5 4 0 5s5 3.5 0 4.5");
}

</style>
