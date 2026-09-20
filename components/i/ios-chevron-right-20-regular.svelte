<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wz9fznbse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:ios-chevron-right-20-regular" {...props}></Icon>
<style>
:global(.wz9fznbse) {
  fill: currentColor;
  d: path("M12.646 5.854a.5.5 0 0 1 .708-.708l4.5 4.5a.5.5 0 0 1 0 .708l-4.5 4.5a.5.5 0 0 1-.708-.708L16.793 10z");
}

</style>
