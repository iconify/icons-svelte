<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6jab7f2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:kitchen-outline-sharp" {...props}></Icon>
<style>
:global(.y6jab7f2n) {
  fill: currentColor;
  d: path("M8 8V5h2v3zm0 9v-5h2v5zm-4 5V2h16v20zm2-2h12v-9H6zM6 9h12V4H6z");
}

</style>
