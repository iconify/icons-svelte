<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1b9j_3vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-up-right-large-fill-round" {...props}></Icon>
<style>
:global(.x1b9j_3vc) {
  fill: currentColor;
  d: path("M18 5a1 1 0 0 1 1 1v8a1 1 0 0 1-2 0V8.414L6.707 18.707a.999.999 0 1 1-1.414-1.414L15.586 7H10a1 1 0 0 1 0-2Z");
}

</style>
