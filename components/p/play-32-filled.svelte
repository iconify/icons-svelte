<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v8cs3bcys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:play-32-filled" {...props}></Icon>
<style>
:global(.v8cs3bcys) {
  fill: currentColor;
  d: path("M12.225 4.462C9.89 3.142 7 4.827 7 7.508V24.5c0 2.682 2.892 4.368 5.226 3.045l14.997-8.498c2.367-1.341 2.366-4.751 0-6.091z");
}

</style>
