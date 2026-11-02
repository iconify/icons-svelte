<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h0wwvqb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:brush-sharp" {...props}></Icon>
<style>
:global(.h0wwvqb9x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 19v-5H6V3h12v11h-4v5a2 2 0 1 1-4 0m-4-9h12m-8-7v3m4-3v3");
}

</style>
