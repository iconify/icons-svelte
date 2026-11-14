<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s02oj0b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:loan-credit-assessment" {...props}></Icon>
<style>
:global(.s02oj0b-s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.636 19.364A9 9 0 0 1 4.206 8.5m1.43-1.864a9 9 0 0 1 12.728 0m1.43 1.864a9 9 0 0 1-1.43 10.864M12 13l4-4.5M10.25 13a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

</style>
