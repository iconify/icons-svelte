<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4v-ekbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-u-fill-sharp" {...props}></Icon>
<style>
:global(.q4v-ekbdh) {
  fill: currentColor;
  d: path("M8 16a4 4 0 0 0 8 0V4a1 1 0 0 1 2 0v12a6 6 0 1 1-12 0V4a1 1 0 0 1 2 0Z");
}

</style>
