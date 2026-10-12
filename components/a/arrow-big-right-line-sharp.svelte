<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjrsl5b8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:arrow-big-right-line-sharp" {...props}></Icon>
<style>
:global(.zjrsl5b8t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m20.01 12.99l-6.77 6.77l-.99.99V15.5h-9v-7h9V3.25l.99.99l6.77 6.77l.99.99z");
}

</style>
