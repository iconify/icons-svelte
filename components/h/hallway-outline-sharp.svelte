<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdl7fqbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:hallway-outline-sharp" {...props}></Icon>
<style>
:global(.tdl7fqbai) {
  fill: currentColor;
  d: path("M3 22V4h5l4-4l4 4h5v18zm2-2h14V6H5zm1-2h12l-3.75-5l-3 4L9 14zm4.1-14h3.8L12 2.1zM5 20V6z");
}

</style>
