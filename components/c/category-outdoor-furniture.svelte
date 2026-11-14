<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y08aasyje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:category-outdoor-furniture" {...props}></Icon>
<style>
:global(.y08aasyje) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11a9.5 8 0 0 1 19 0ZM12 3v18.5M5.5 16h13M9 21.5h6M12 3l-4.5 8M12 3l4.5 8");
}

</style>
