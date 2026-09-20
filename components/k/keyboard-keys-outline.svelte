<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmxtikbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:keyboard-keys-outline" {...props}></Icon>
<style>
:global(.kmxtikbee) {
  fill: currentColor;
  d: path("M7.23 16.77v-1.54h9.54v1.54zm-4-4v-1.54h1.54v1.54zm4 0v-1.54h1.54v1.54zm4 0v-1.54h1.54v1.54zm4 0v-1.54h1.54v1.54zm4 0v-1.54h1.54v1.54zm-16-4V7.23h1.54v1.54zm4 0V7.23h1.54v1.54zm4 0V7.23h1.54v1.54zm4 0V7.23h1.54v1.54zm4 0V7.23h1.54v1.54z");
}

</style>
