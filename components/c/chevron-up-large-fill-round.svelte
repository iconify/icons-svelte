<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrqzfebyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-up-large-fill-round" {...props}></Icon>
<style>
:global(.hrqzfebyp) {
  fill: currentColor;
  d: path("m12 10.414l-5.293 5.293a.999.999 0 1 1-1.414-1.414l6-6a1 1 0 0 1 1.414 0l6 6a.999.999 0 1 1-1.414 1.414Z");
}

</style>
