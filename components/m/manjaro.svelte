<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="fbp7odb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:manjaro" {...props}></Icon>
<style>
:global(.fbp7odb2g) {
  fill: var(--svg-color--35bf5c, #35bf5c);
  d: path("M256 0v256h-74.925V0zm-90.54 90.536V256H90.535V90.536zm0-90.536v74.925H74.67V256H0V0z");
}

</style>
