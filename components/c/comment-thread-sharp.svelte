<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u81nocbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:comment-thread-sharp" {...props}></Icon>
<style>
:global(.u81nocbro) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.75v-2.5h13.5v8.5H2.75v-2.5Zm3.5 1.75h6.5M6.5 11.75v5.75h2.75m0-3.25h12v6.5h-12z");
}

</style>
