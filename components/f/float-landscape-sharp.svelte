<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-u27x01k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:float-landscape-sharp" {...props}></Icon>
<style>
:global(.i-u27x01k) {
  fill: currentColor;
  d: path("M2 20V4h20v7h-7v9Zm15 0v-7h5v7Z");
}

</style>
