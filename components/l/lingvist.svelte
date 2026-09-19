<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z9-rgybaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lingvist" {...props}></Icon>
<style>
:global(.z9-rgybaa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 12.5v23m19-23.5l20 11.986m0 .068l-20 11.947m-1.284-10.674L4.5 36");
}

</style>
