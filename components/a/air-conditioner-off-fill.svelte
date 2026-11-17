<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-bjb3nah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:air-conditioner-off-fill" {...props}></Icon>
<style>
:global(.x-bjb3nah) {
  fill: currentColor;
  d: path("M5 2h14a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3m2 5a1 1 0 0 0 0 2h10a1 1 0 0 0 0-2Z");
}

</style>
