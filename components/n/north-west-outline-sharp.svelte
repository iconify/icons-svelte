<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjfbkjutw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:north-west-outline-sharp" {...props}></Icon>
<style>
:global(.zjfbkjutw) {
  fill: currentColor;
  d: path("M18.292 19L7 7.708V15H6V6h9v1H7.708L19 18.292z");
}

</style>
