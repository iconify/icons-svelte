<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="todgztbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:eyebrow-pencil" {...props}></Icon>
<style>
:global(.todgztbzj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 17.5L12 10l5-2l-2 5l-7.5 7.5Zm-1-10q6.5-6 17-2.5M12 10l3 3");
}

</style>
