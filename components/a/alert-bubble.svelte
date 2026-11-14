<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncbn2bczq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:alert-bubble" {...props}></Icon>
<style>
:global(.ncbn2bczq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 19.5l-3.5 1L5 17a8.5 8.5 0 1 1 2.5 2.5M12 7v6m0 3.5h.01");
}

</style>
