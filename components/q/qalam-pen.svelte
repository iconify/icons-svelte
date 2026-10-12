<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h36gsti_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:qalam-pen" {...props}></Icon>
<style>
:global(.h36gsti_n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20.5 3.5L10.25 13.75m1.47 1.47l-2.94-2.94q-.53-.53-.88.13l-3.8 7.18q-.35.66.31.31l7.18-3.8q.66-.35.13-.88M9.5 20.25c2.5-1.5 5 .75 7.5-.75c1.25-.75 2.5-1 3.75-.5");
}

</style>
