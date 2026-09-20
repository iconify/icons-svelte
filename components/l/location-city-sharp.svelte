<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3o9r30ch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:location-city-sharp" {...props}></Icon>
<style>
:global(.q3o9r30ch) {
  fill: currentColor;
  d: path("M5.039 20.154v-13H9.5v-3.27L12 1.5l2.5 2.385v7.269h4.462v9zm1-1h3v-3h-3zm0-4h3v-3h-3zm0-4h3v-3h-3zm4.461 8h3v-3h-3zm0-4h3v-3h-3zm0-4h3v-3h-3zm0-4h3v-3h-3zm4.462 12h3v-3h-3zm0-4h3v-3h-3z");
}

</style>
