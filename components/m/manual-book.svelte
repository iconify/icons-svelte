<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjsgskuzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:manual-book" {...props}></Icon>
<style>
:global(.tjsgskuzv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 19V5a2.5 2.5 0 0 1 2.5-2.5H19v19H7.5A2.5 2.5 0 0 1 5 19a2.5 2.5 0 0 1 2.5-2.5H19M9 7h6m-6 4h4");
}

</style>
