<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r3qeus1wg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:campaign-delete" {...props}></Icon>
<style>
:global(.r3qeus1wg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.164 15.955L7.5 13.5h-4v-5h4l9.5-5v8.665M6 13.5l1.5 5M15 15h6m-5 0v5.5q0 1 1 1h2q1 0 1-1V15");
}

</style>
