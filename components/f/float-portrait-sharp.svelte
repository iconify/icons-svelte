<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlk4w4c1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:float-portrait-sharp" {...props}></Icon>
<style>
:global(.zlk4w4c1a) {
  fill: currentColor;
  d: path("M15 22v-7h5v7ZM4 22V2h16v11h-7v9Z");
}

</style>
