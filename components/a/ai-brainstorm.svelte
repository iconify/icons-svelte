<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co-doedka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ai-brainstorm" {...props}></Icon>
<style>
:global(.co-doedka) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 18v-1.25a5 5 0 1 1 5 0V18Zm.5 3h4M12 2.5v2m-7.25.75L6.5 7m11 0l1.75-1.75");
}

</style>
