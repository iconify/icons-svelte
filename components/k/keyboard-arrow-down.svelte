<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx8hedcya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:keyboard-arrow-down" {...props}></Icon>
<style>
:global(.xx8hedcya) {
  fill: currentColor;
  d: path("m12 15.4l-6-6L7.4 8l4.6 4.6L16.6 8L18 9.4z");
}

</style>
