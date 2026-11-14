<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="haa7eybre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:alert-minimal" {...props}></Icon>
<style>
:global(.haa7eybre) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5za2 2 0 0 1 2 2v9a2 2 0 0 1-2 2a2 2 0 0 1-2-2v-9a2 2 0 0 1 2-2M10.25 20a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
