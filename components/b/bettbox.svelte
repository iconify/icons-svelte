<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aszpx4bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:bettbox" {...props}></Icon>
<style>
:global(.aszpx4bsz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.559 12.358l-6.92 23.064h6.17l6.92-23.064zM15.865 8.391L6.5 39.61h8.52l9.366-31.22zM37.02 16.25l-4.628 15.426h4.48L41.5 16.25z");
}

</style>
