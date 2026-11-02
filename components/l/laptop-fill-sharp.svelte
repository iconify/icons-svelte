<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gc2-nsv5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:laptop-fill-sharp" {...props}></Icon>
<style>
:global(.gc2-nsv5c) {
  fill: currentColor;
  d: path("M4 4a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v11h1a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h1Zm16 13H4v2h16Z");
}

</style>
