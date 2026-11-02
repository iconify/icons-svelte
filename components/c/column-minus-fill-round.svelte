<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukcc3lbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:column-minus-fill-round" {...props}></Icon>
<style>
:global(.ukcc3lbke) {
  fill: currentColor;
  d: path("M3 7a4 4 0 0 1 8 0v10a4 4 0 0 1-8 0Zm17 4a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2Z");
}

</style>
