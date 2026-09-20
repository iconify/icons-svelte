<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mle8oo52s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:image-sharp" {...props}></Icon>
<style>
:global(.mle8oo52s) {
  fill: currentColor;
  d: path("M6 17h12l-3.75-5l-3 4L9 13zm-3 4V3h18v18z");
}

</style>
