<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0616cctn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:pause-outline-sharp" {...props}></Icon>
<style>
:global(.b0616cctn) {
  fill: currentColor;
  d: path("M13 19V5h6v14zm-8 0V5h6v14zm10-2h2V7h-2zm-8 0h2V7H7zM7 7v10zm8 0v10z");
}

</style>
