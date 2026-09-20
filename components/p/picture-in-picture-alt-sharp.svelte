<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jk0i7owuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:picture-in-picture-alt-sharp" {...props}></Icon>
<style>
:global(.jk0i7owuz) {
  fill: currentColor;
  d: path("M3 19V5h18v14zm8.308-2.039H19V11.27h-7.692zm3.846-2.845");
}

</style>
