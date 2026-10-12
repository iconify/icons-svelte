<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vk8nymj7f"/><path class="s-1jpob7n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hazard-lights" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s-1jpob7n) {
  d: path("m12.49 10.12l3.27 5.76q.49.87-.51.87h-6.5q-1 0-.51-.87l3.27-5.76q.49-.87.98 0");
}

:global(.vk8nymj7f) {
  d: path("M12.97 4.75L20.28 18q.97 1.75-1.03 1.75H4.75q-2 0-1.03-1.75l7.31-13.25q.97-1.75 1.94 0");
}

</style>
