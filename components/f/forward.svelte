<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8twl3rcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:forward" {...props}></Icon>
<style>
:global(.f8twl3rcu) {
  fill: currentColor;
  d: path("M12 8V4l8 8l-8 8v-4H4V8z");
}

</style>
