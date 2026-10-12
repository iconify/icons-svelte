<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9zz0qbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:half-star-sharp" {...props}></Icon>
<style>
:global(.k9zz0qbqs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.76h-.21l-.21.51l-1.72 4.14l-.42 1.02l-1.09.09l-4.48.35l-1.1.08l.84.72l3.42 2.91l.83.71l-.25 1.07l-1.05 4.37l-.26 1.07l.94-.58l3.82-2.34l.47-.29H12Z");
}

</style>
