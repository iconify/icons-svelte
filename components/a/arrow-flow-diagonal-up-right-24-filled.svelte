<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l12ip2c_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-flow-diagonal-up-right-24-filled" {...props}></Icon>
<style>
:global(.l12ip2c_y) {
  fill: currentColor;
  d: path("M12.75 4a.75.75 0 0 0 0 1.5h4.69l-8.192 8.191a4 4 0 1 0 1.06 1.06l8.192-8.19v4.689a.75.75 0 0 0 1.5 0v-6.5a.75.75 0 0 0-.75-.75z");
}

</style>
