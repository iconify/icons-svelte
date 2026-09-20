<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oygjvsc9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:description-sharp" {...props}></Icon>
<style>
:global(.oygjvsc9b) {
  fill: currentColor;
  d: path("M8 18h8v-2H8zm0-4h8v-2H8zm-4 8V2h10l6 6v14zm9-13h5l-5-5z");
}

</style>
