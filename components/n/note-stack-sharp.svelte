<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sonaldb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:note-stack-sharp" {...props}></Icon>
<style>
:global(.sonaldb2u) {
  fill: currentColor;
  d: path("M8 21V7.994h13v8.583L16.577 21zm12-5h-4v4zM5.012 17.806L2.752 5.01l12.794-2.259l.504 2.864H5.617v12.082z");
}

</style>
