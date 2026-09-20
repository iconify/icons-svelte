<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="z2bt2kjrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:number-five-bold" {...props}></Icon>
<style>
:global(.z2bt2kjrb) {
  fill: currentColor;
  d: path("M180 160a60 60 0 0 1-100 44.72a12 12 0 1 1 16-17.88a36 36 0 1 0 .69-54.28a12 12 0 0 1-19.54-11.49l15.08-75.42A12 12 0 0 1 104 36h64a12 12 0 0 1 0 24h-54.16l-8.36 41.79A60 60 0 0 1 180 160");
}

</style>
