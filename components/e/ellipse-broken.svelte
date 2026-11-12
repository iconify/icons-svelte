<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly88a1ihf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ellipse-broken" {...props}></Icon>
<style>
:global(.ly88a1ihf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 5.5825C9.2249 5.2078 10.5778 5 12 5C17.5228 5 22 8.134 22 12C22 15.866 17.5228 19 12 19C6.4772 19 2 15.866 2 12C2 10.9264 2.3453 9.9093 2.9623 9");
}

</style>
