<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msn5gdzzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:magnification-large-sharp" {...props}></Icon>
<style>
:global(.msn5gdzzt) {
  fill: currentColor;
  d: path("M5 15h12V7H5zm-3 5V4h20v16z");
}

</style>
