<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5rsc8vss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:maxi-dress" {...props}></Icon>
<style>
:global(.k5rsc8vss) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 2.5v3l-1 5L4 21.5h16l-4.25-11l-1-5v-3Q12 7 9.25 2.5Zm-1 8h7.5");
}

</style>
