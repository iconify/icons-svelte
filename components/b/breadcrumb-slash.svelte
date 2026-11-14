<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-g92rsly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:breadcrumb-slash" {...props}></Icon>
<style>
:global(.b-g92rsly) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12h4m11 0h4M10 16l4-8");
}

</style>
