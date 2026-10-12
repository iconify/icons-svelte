<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5b_pccus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:high-chair" {...props}></Icon>
<style>
:global(.z5b_pccus) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 3.25v9.25m-.75 0h11M11 8.75h9M8.75 12.5L6.5 21.25m8.75-8.75l2.25 8.75M7.46 17.5h9.08");
}

</style>
