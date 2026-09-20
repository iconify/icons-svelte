<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nk5agebqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:process-chart" {...props}></Icon>
<style>
:global(.nk5agebqs) {
  fill: currentColor;
  d: path("m3.646 17.777l-.896-.439L8.308 6.224l.896.438zm6.023 0l-.896-.438l5.558-11.116l.896.438zm6.023 0l-.896-.438l5.558-11.116l.896.439z");
}

</style>
