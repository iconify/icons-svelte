<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2-hahz3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:label-important-rounded" {...props}></Icon>
<style>
:global(.p2-hahz3g) {
  fill: currentColor;
  d: path("M14.692 19H4.654q-.51 0-.727-.454t.1-.857l4.165-5.304q.135-.173.135-.385t-.135-.385L4.027 6.293q-.317-.403-.1-.857t.727-.454h10.019q.379 0 .718.154q.338.155.555.453l4.27 5.404q.361.448.361 1.008t-.362 1.008l-4.25 5.384q-.217.299-.556.453q-.338.155-.717.155");
}

</style>
